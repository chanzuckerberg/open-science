---
title: Contributing to this project
layout: default
---

> If you have general questions or feedback about this project
> and do not want to create a GitHub account to interact with the project team,
> please see our [support guidelines](/open-science/SUPPORT).

- [Issues](#issues)
- [Pull requests](#pull-requests)
  - [PRs for website content](#prs-for-website-content)
    - [Organization of website content](#organization-of-website-content)
    - [Tips for writing website content](#tips-for-writing-website-content)
    - [Submitting a PR for website content](#submitting-a-pr-for-website-content)
  - [PRs for web styling](#prs-for-web-styling)
    - [Technical information about the site](#technical-information-about-the-site)
    - [Previewing the site locally](#previewing-the-site-locally)
  - [Additional Resources](#additional-resources)

Thanks for considering making a contribution to this project!
We are very happy to help share information about what tools and resources you've found useful,
so other biomedical researchers can improve access to research deliverables as well.

> This project adheres to the [Contributor Covenant Code of Conduct](/open-science/CODE_OF_CONDUCT).
> By participating, you are expected to uphold this code.
> Please report unacceptable behavior to <opensource@chanzuckerberg.com>.

These contribution guidelines assume you have a GitHub account
and are able to contribute via the project's [GitHub repository](https://github.com/chanzuckerberg/open-science).
If you are not familiar with GitHub,
you may find it useful to read through GitHub's [Quickstart guide](https://docs.github.com/en/get-started/quickstart/hello-world).

In the spirit of open science,
this project is developed using the same best practices we recommend for open source software projects.
If you are new to GitHub,
developing content for this site is a great, low-stakes way to learn how it works!
We're happy to help you get started.

Contributions can come in a few different forms:

- **Suggesting content**: ideas for new content, or recommendations to update existing information
- **Bug reports**: identifying broken links and other technical problems with the website

You can share these contributions in two main ways via GitHub:

- [Issues](#issues): ideas for new content, or recommendations to update existing information
- [Pull requests](#pull-requests): identifying broken links and other technical problems with the website

Additional guidance on these two methods of contributing are included below.

> If you believe you have found a security issue,
> please notify us (rather than submitting an issue)
> by emailing <security@chanzuckerberg.com>.

## Issues

[Issues in GitHub](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues) are a great way to communicate with us about this website.
Browse the [existing issues](https://github.com/chanzuckerberg/open-science/issues) to see whether there is a current conversation related to your idea.

The main sets of issue labels for this project include:

- *content*: addition or alteration to website content (about open science)
- *documentation*: everything in the website that's not about open science (like these Contribution guidelines)
- *infrastructure*: improving how the website operates
- *question*: requests for further information, often used in conjunction with another label, like *content*

You are welcome to add thoughts to existing issues,
including comments and reactions to posts in the issue discussion.
If no conversation about your idea currently exists,
please [submit a new issue](https://github.com/chanzuckerberg/open-science/issues/new).
If you are filing an issue because something isn't rendering correctly on the website,
we appreciate you sharing a screen shot!

## Pull requests

We accept [pull requests (PRs)](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) from forks of our repository.

### PRs for website content

#### Organization of website content

All content for this website can be edited via markdown (`.md`)
files representing each of the pages in the site.

Most content related to open science is found in the following sections:

- Protocols
- Software and Code
- Data
- Preprints and Publications
- Resources

Each section is represented by:

- subdirectory labeled with the section name (e.g., `code/`); note that "Data" is represented by `data_sharing/` to avoid conflicts with Jekyll's assumptions about `data/`
- an overview page, `overview.md`, that describes all topics within the section and includes a table of contents with links to all topics
- additional markdown files representing topic pages within the section; these are created when the content for a topic becomes too lengthy to include in the main overview page

If you would like to add additional pages to a section,
use one of the existing files as a template and save it in the appropriate subdirectory.
Also be sure to include the new topic on the overview page and add the new topic to the table of contents.
The table of contents can be manually created,
or automatically added using [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) in VSCode.

Other `.md` files from the [repository](https://github.com/chanzuckerberg/open-science/)
rendered as content in the site are located at the top level of the directory.
These files include:

- `index`: front page of website
- `about`: basic descriptions modified from README and links to the files below
- `CODE_OF_CONDUCT`: standard language required by CZI
- `CONTRIBUTING`: this file
- `LICENSE`: standard MIT license
- `SECURITY`: standard language required by CZI
- `SUPPORT`: basic content recommended by CZI

The `README` is not rendered in the website,
and is used only for viewing on GitHub.

#### Tips for writing website content

[**GitHub Flavored Markdown** ](https://github.github.com/gfm/)
is the basic method through which files are rendered for this project.
[This cheat sheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
is a good place to look for a quick reference on markdown formatting.

**Images** can be added using standard Markdown syntax.
If you are including an image file,
please format it as `png` or `jpg` and place it in `images/`.
Include a relative path to the image file where it should appear in the markdown file:

`![Description of image](../../images/image.png)`

**Links** to other locations in the site should be prefaced with `/open-science/`
and reference the location and filename of the markdown file containing the content.
Prepending the repository name is necessary because we render the site using GitHub Pages'
automated backend and the folder name (repository) 
is required to disambiguate from other websites rendered in the same organization.
For example:

- About page: `/open-science/about`
- Data overview: `/open-science/data_sharing/overview`

The trailing slash at the end of the path is optional.

It's also possible to use Jekyll's site variables (`site.url` and `site.baseurl`)
to render links.
However, if you are building the site locally,
you'll need to restart to the server to see changes using these tags take effect
(even if you have enabled auto-regeneration).
Given this complexity,
we have chosen to generally use the more straightforward method of prepending with the repository name (`open-science`).
For more information on formatting links, 
we recommend [this article](https://mademistakes.com/mastering-jekyll/site-url-baseurl/).

**Videos** can be linked as per the instructions above,
or can be embedded on a page following general instructions [here](https://github.com/nathancy/jekyll-embed-video).
The example file [`wistiaPlayer.html`](https://github.com/chanzuckerberg/open-science/blob/main/_includes/wistiaPlayer.html)
can be used to demonstrate the approach.
On the page where the video should appear,
place a single line of code: `include wistiaPlayer.html`.
This code should be formatted in Liquid syntax as a [tag](https://shopify.github.io/liquid/basics/introduction/#tags)
with curly brace percentage delimiters.

#### Submitting a PR for website content

In most cases, you'll be able to create your PR via the GitHub web interface.
[the process for proposing changes via a pull request](https://guides.github.com/introduction/flow/) is:

1. [Fork](https://github.com/chanzuckerberg/open-science/fork) the project
2. Create a new [branch](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository#creating-a-branch).
3. Alter the content on the page using the [editor in the web interface](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files).
4. [Submit a pull request](https://github.com/chanzuckerberg/open-science/compare) to our repository from your fork's branch containing the changes.

Each pull request should change *one* thing,
where a thing represents an easily described idea. 
Because this is a website, rather than a code development project, 
it can sometimes be hard to identify what represents a single thing. 
In general, a PR for this project will affect only one section of the website 
(e.g., "Software and Code"). 
It's ok to submit more than one pull request!

### PRs for web styling

#### Technical information about the site

This website is created using [jekyll](https://jekyllrb.com/).
The instructions below should be sufficient for most folks,
but additional information is available in the [jekyll documentation](https://jekyllrb.com/docs/).

The theme used for this site is [minimal](https://github.com/pages-themes/minimal).
Please see that project's documentation for more information on customization, 
including configuration variables, stylesheets, and layouts.

The main files involving site layout, navigation, and styling include:

- `_layouts/default.html`: dictates arrangement and appearance of all pages
- `_includes/head-custom.html`: proliferates tracking for web analytics
- `_config.yml`: configures theme, pages, and web analytics

If you would like to make changes to the web styling,
please preview your changes by building the site locally before submitting a pull request.

#### Previewing the site locally

If you'd like to preview the theme locally (for example, in the process of proposing a change):

1. Clone this repository (`git clone https://github.com/chanzuckerberg/open-science`)
2. `cd` into the project directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit the server address listed in the output to preview the site in your browser

The `minimal` theme also contains a minimal test suite. 
To run the tests:

- run `script/bootstrap`
- run `script/cibuild`

### Additional Resources

* [Contributing to Open Source on GitHub](https://guides.github.com/activities/contributing-to-open-source/)
* [Using Pull Requests](https://help.github.com/articles/using-pull-requests/)
* [GitHub Help](https://help.github.com)

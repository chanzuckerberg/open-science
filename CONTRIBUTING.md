---
layout: default
---

# Contributing to this project

> If you have general questions or feedback about this project,
> please see our [support guidelines](/open-science/SUPPORT).

Thanks for considering making a contribution to this project!
We are very happy to help share information about what tools and resources
other biomedical researchers have found useful in their work.
These contribution guidelines assume you have a GitHub account
and are able to contribute to the project via the project's [GitHub repository](https://github.com/chanzuckerberg/open-science).

> This project adheres to the [Contributor Covenant Code of Conduct](/open-science/CODE_OF_CONDUCT).
> By participating, you are expected to uphold this code.
> Please report unacceptable behavior to <opensource@chanzuckerberg.com>.

Contributions can come in a few different forms:

- **Suggesting content**: ideas for new content, or recommendations to update existing information
- **Bug reports**: identifying broken links and other technical problems with the website

You can share these contributions in two main ways via GitHub:

- [Issues](#issues): ideas for new content, or recommendations to update existing information
- [Pull requests](#pull-requests): identifying broken links and other technical problems with the website

Additional guidance on these two contribution types are included below.

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

Most content related to open science is found in the `collections/` folder of the repository.
Each collection is represented by a subdirectory with the name prefaced in an underscore (e.g., *_code/*).
Each collection includes one or more pages represented by a markdown (`.md`) file.

We accept [pull requests (PRs)](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) from forks of our repository.

### PRs for website content

In most cases, you'll be able to create your PR via the GitHub web interface.
[the process for proposing changes via a pull request](https://guides.github.com/introduction/flow/) is:

1. [Fork](https://github.com/chanzuckerberg/open-science/fork) and clone the project
2. Create a new [branch](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository).
5. Alter the content on the page using the [editor in the web interface](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files).
6. [Submit a pull request](https://github.com/chanzuckerberg/open-science/compare) to our repository from your fork's branch containing the changes.

Each pull request should change *one* thing. Because this is a website, rather than a code development project, it can sometimes be hard to identify what represents a single thing. In general, a PR for this project will affect only one section of the website (e.g., "Software and Code"). It's ok to submit more than one pull request!

### PRs for web styling

This website is created using [jekyll](https://jekyllrb.com/).
The instructions below should be sufficient for most folks,
but additional information is available in the [jekyll documentation](https://jekyllrb.com/docs/).

The theme used for this site is [minimal](https://github.com/pages-themes/minimal).
Please see that project's documentation for more information on customization, 
including configuration variables, stylesheets, and layouts.

#### Previewing the site locally

If you'd like to preview the theme locally (for example, in the process of proposing a change):

1. Clone this repository (`git clone https://github.com/chanzuckerberg/open-science`)
2. `cd` into the project directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit the server address listed in the output to preview the site in your browser

#### Running tests

The `minimal` theme contains a minimal test suite. 
To run the tests:
- run `script/bootstrap`
- run `script/cibuild`

### Additional Resources

* [Contributing to Open Source on GitHub](https://guides.github.com/activities/contributing-to-open-source/)
* [Using Pull Requests](https://help.github.com/articles/using-pull-requests/)
* [GitHub Help](https://help.github.com)

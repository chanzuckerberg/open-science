---
layout: default
---

# Contributing to this project

> If you are looking for assistance in working with this project,
> please check out our [support guidelines](SUPPORT.md).

Thanks for considering making a contribution to this project!
We are very happy to help share information about what tools and resources
other biomedical researchers have found useful in their work.

> This project adheres to the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md).
> By participating, you are expected to uphold this code.
> Please report unacceptable behavior to opensource@chanzuckerberg.com.

Regardless of your career level, area of biomedical expertise, 
or experience with open science,
your feedback is valuable to us!
We are happy to accept a variety of contributions:

- [Suggesting content](#suggesting-content): ideas for new content, or recommendations to update existing information, either via email/Slack or GitHub
- [Bug reports](#bug-reports): identifying broken links and other technical problems with the website, either via email/Slack or GitHub
- [Pull requests](#pull-requests): Direct submissions of code and/or website content, via GitHub

> If you believe you have found a security issue,
> please notify us (rather than submitting an issue)
> by emailing security@chanzuckerberg.com .

## Suggesting content

> This section is **Under Construction**

ideas for new content, or recommendations to update existing information, either via email/Slack or GitHub

- creating issues to suggest new content
- creating issues to recommend changes/enhancements to existing content
- commenting on or reacting to existing issues and pull requests
- sharing feedback described above via email or Slack

## Bug reports

> This section is **Under Construction**

Think you found a bug? Please check [the list of open issues](https://github.com/pages-themes/minimal/issues) to see if your bug has already been reported. If it hasn't please [submit a new issue](https://github.com/pages-themes/minimal/issues/new).

Here are a few tips for writing *great* bug reports:

* Describe the specific problem (e.g., "widget doesn't turn clockwise" versus "getting an error")
* Include the steps to reproduce the bug, what you expected to happen, and what happened instead
* Check that you are using the latest version of the project and its dependencies
* Include what version of the project your using, as well as any relevant dependencies
* Only include one bug per issue. If you have discovered two bugs, please file two issues
* Even if you don't know how to fix the bug, including a failing test may help others track it down

## Pull requests

> This section is **Under construction**

### PR guidelines

* If you are making visual changes, include a screenshot of what the affected element looks like, both before and after.
* Follow the [Jekyll style guide](https://ben.balter.com/jekyll-style-guide).
* If you are changing any user-facing functionality, please be sure to update the documentation
* Each pull request should implement **one** feature or bug fix. If you want to add or fix more than one thing, submit more than one pull request
* Do not commit changes to files that are irrelevant to your feature or bug fix
* Don't bump the version number in your pull request (it will be bumped prior to release)
* Write [a good commit message](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)

### Submitting a PR

At a high level, [the process for proposing changes](https://guides.github.com/introduction/flow/) is:

1. [Fork](https://github.com/pages-themes/minimal/fork) and clone the project
2. Configure and install the dependencies: `script/bootstrap`
3. Make sure the tests pass on your machine: `script/cibuild`
4. Create a new branch: `git checkout -b my-branch-name`
5. Make your change, add tests, and make sure the tests still pass
6. Push to your fork and [submit a pull request](https://github.com/pages-themes/minimal/compare)
7. Pat your self on the back and wait for your pull request to be reviewed and merged

### Your first contribution

We'd love for you to contribute to the project. Unsure where to begin contributing to the Minimal theme? You can start by looking through these "good first issue" and "help wanted" issues:

* [Good first issues](https://github.com/pages-themes/minimal/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) - issues which should only require a few lines of code and a test or two
* [Help wanted issues](https://github.com/pages-themes/minimal/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) - issues which may be a bit more involved, but are specifically seeking community contributions

### Additional Resources

* [Contributing to Open Source on GitHub](https://guides.github.com/activities/contributing-to-open-source/)
* [Using Pull Requests](https://help.github.com/articles/using-pull-requests/)
* [GitHub Help](https://help.github.com)

## Technical information

This website is created using [jekyll](https://jekyllrb.com/).
The instructions below should be sufficient for most folks,
but additional information is available in the [jekyll documentation](https://jekyllrb.com/docs/).

The theme used for this site is [minimal](https://github.com/pages-themes/minimal).
Please see that project's documentation for more information on customization, 
including configuration variables, stylesheets, and layouts.

### Previewing the site locally

If you'd like to preview the theme locally (for example, in the process of proposing a change):

1. Clone this repository (`git clone https://github.com/chanzuckerberg/open-science`)
2. `cd` into the project directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit the server address listed in the output to preview the site in your browser

### Running tests

The `minimal` theme contains a minimal test suite. 
To run the tests:
- run `script/bootstrap`
- run `script/cibuild`

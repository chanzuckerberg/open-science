---
title: Code development
category: code
layout: default
---

**Topics on this page:**
- [Fundamental concepts in coding](#fundamental-concepts-in-coding)
  - [Learning to code](#learning-to-code)
  - [Version control with Git and GitHub](#version-control-with-git-and-github)
  - [Contributing to a project](#contributing-to-a-project)
  - [Code architecture and design](#code-architecture-and-design)
  - [Strategies for debugging](#strategies-for-debugging)
  - [Testing and continuous integration](#testing-and-continuous-integration)
- [Writing software for others to use](#writing-software-for-others-to-use)
  - [Documentation](#documentation)
  - [Licensing](#licensing)
  - [Code citations](#code-citations)
  - [User interfaces](#user-interfaces)
  - [Interoperability and shared infrastructure](#interoperability-and-shared-infrastructure)
  - [Containerizing code](#containerizing-code)

This topic page focuses on general programming practices,
as well as developing programming skills to create reproducible code.
The information is appropriate for people new to coding,
programmers who are new to data-intensive research,
and software developers interested in developing open source research software.

## Fundamental concepts in coding

The following resources provide a general overview of best practices in computational research:

- [Good enough practices in scientific computing](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510)
- [Ten Simple Rules for Effective Computational Research](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003506)
- [Ten Simple Rules for Reproducible Computational Research](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285)
- [Ten Simple Rules for Developing Usable Software in Computational Biology](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005265)
- [Ten simple rules for making research software more robust](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005412)

### Learning to code

If you are a clinical or wet-lab researcher who is interested in learning to code,
this article helps you understand the process of coding,
and compares some of the most common programming languages: 
[Ten simple rules for biologists learning to program](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005871).

For tutorials that will teach you to code,
please see the [Resources section](/open-science/resources)
for organizations involved in training.

### Version control with Git and GitHub

Version control is a foundational tool used in code development to track changes that occur
to files over time.
[Git](https://git-scm.com/about) 
is a version control software frequently used in research computing,
with [GitHub](https://help.github.com/en/github) 
a corresponding public repository in which projects tracked with Git
can be viewed and used.

[GitHub Learning Lab](https://lab.github.com/) contains a large number of free tutorials
for tasks relevant to writing and sharing research code, including:

- [Introduction to GitHub](https://lab.github.com/githubtraining/introduction-to-github)
- Creating websites with [GitHub Pages](https://lab.github.com/githubtraining/github-pages)

### Contributing to a project

Beginning to work on your own project can be a daunting task.
It may be useful for you to take a look at how other similar projects operate.
Many software development projects for research tools are hosted on GitHub,
and would be grateful for you to participate in their project.
If you're not familiar with GitHub,
please see the [version control section](#version-control-with-git-and-github)
to get started.

Most projects outline how you can contribute to their project in particular.
The following resources include some general guidelines for contributing to other people's
open source projects:

- [How to contribute](https://opensource.guide/how-to-contribute/)
- [Contributing code](https://opensource.creativecommons.org/contributing-code/)

### Code architecture and design

**Under construction**

[Refactoring catalog](https://refactoring.com/catalog/)

### Strategies for debugging

**Under construction**

[Programming with Python: Debugging](https://swcarpentry.github.io/python-novice-inflammation/11-debugging/index.html)
from Software Carpentry

### Testing and continuous integration

**Under construction**

[Testing Software](https://merely-useful.tech/py-rse/testing.html)
from Research Software Engineering with Python

## Writing software for others to use

While the section above highlights foundational concepts in programming,
this section focuses on writing code that other researchers will be able to reuse
(including your future self!).

For a comprehensive overview of overall tools and approaches when developing software,
please see [Research Software Engineering with Python](https://merely-useful.tech/py-rse/index.html).
This book integrates across concepts highlighted in the section above,
as well as the following subsections.

### Documentation

**Under construction**

- [Ten simple rules for documenting scientific software](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006561)
- [The Types, Roles, and Practices of Documentation in Data Analytics Open Source Software Libraries: A Collaborative Ethnography of Documentation Work](https://stuartgeiger.com/articles/2018-05-28-cscw-documentation/)

Please see [Tutorials and other user support on the Collaborative research software engineering projects page]
for more information about developing more extensive and formally structured user documentation for software.

### Licensing

**Under construction**

[Include a license](https://merely-useful.tech/py-rse/teams.html#teams-license)
from Research Software Engineering with Python

### Code citations

Clearly communicating how you'd like your software to be cited is essential
for receiving credit for the work you do in software development.
The following approaches represent separate (but complementary)
approaches to ensuring you can track when other researchers 
publish research using your software.

For more information on these issues, 
please see products from the [FORCE11 Software Citation Implementation Working Group](https://github.com/force11/force11-sciwg#group-products).

**Make it clear to users how your software should be cited in scholarly work.**
Some developers include instructions for citation within the user interface,
while other times the preferred citation may appear on in the GitHub repository's README 
or on the software's documentation website.
GitHub also allows for [standard `CITATION.cff` files](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files)
that will automatically render in a variety of bibliographic formats.

**Engage in peer review of your code.**
Peer review of software is a separate process from the standard peer review process for scientific research (see below),
and focuses more on the standards of the code itself (which is often not formally reviewed with standard publication review).
The following organizations feature peer review mechanisms for software packages:

- [Software Review from ROpenSci](https://ropensci.org/software-review/)
- [pyOpenSci](https://www.pyopensci.org/contributing-guide/intro.html)

**Publish a manuscript about your software.**
Unlike peer review of software (see above),
submitting a publication describing your software focuses more on the narrative of the article to be published,
rather than code comprising the software. 
The following sources provide more information about how and where to publish a peer-reviewed manuscript on your software:

- [The Journal of Open Source Software](https://joss.theoj.org/)
- [List of journals that accept submissions that are primarily about the software](https://www.software.ac.uk/which-journals-should-i-publish-my-software)

### User interfaces

**Under construction**

[GUIs for research software: Why are they relevant?](https://zenodo.org/record/4722579#.YYnA79bMJ6E)

Resources for accessibility:

- [Chartability](https://chartability.fizz.studio/)
- [HTML and accessibility](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML)
- [Jupyter Accessibility workshops](https://blog.jupyter.org/join-us-for-the-jupyter-accessibility-workshops-part-1-133e0e522d1b)

### Interoperability and shared infrastructure

**Under construction**

[Joint Roadmap for Open Science Tools](https://jrost.org/),
now [Invest in Open Infrastructure](https://investinopen.org/)

### Containerizing code

**Under construction**

[Ten simple rules for writing Dockerfiles for reproducible data science](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1008316)

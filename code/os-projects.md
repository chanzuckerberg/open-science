---
title: Collaborative research software engineering projects
category: code
layout: default
---

**Topics in this section:**
- [Research software as a subset of open source software](#research-software-as-a-subset-of-open-source-software)
- [Project management for research software](#project-management-for-research-software)
  - [Planning for sustainability](#planning-for-sustainability)
  - [Governance](#governance)
  - [Team management](#team-management)
  - [Code review](#code-review)
- [Community development](#community-development)
  - [Diverse, equitable, and inclusive communities](#diverse-equitable-and-inclusive-communities)
  - [Code of conduct](#code-of-conduct)
  - [Contribution guidelines](#contribution-guidelines)
  - [Tutorials and other user support](#tutorials-and-other-user-support)
  - [Tracking project metrics](#tracking-project-metrics)

This topic page provides support to open source software engineering projects developed by teams of researchers.
The information is appropriate for projects that would like to develop better processes for operating as a team
and/or
develop inclusive communities around their projects. 

## Research software as a subset of open source software

There are many resources for topics presented on this page that speak to open source projects in general.
For example, the following resources are useful for thinking about open source development in general:

- [Producing Open Source Software](https://producingoss.com/)
- [Open Source Archetypes](https://blog.mozilla.org/wp-content/uploads/2018/05/MZOTS_OS_Archetypes_report_ext_scr.pdf)
- [Sustain in 2021](https://sustainoss.org/assets/pdf/Sustain-In-2021-Event-Report.pdf)

However, this page is specifically focused on open source projects supporting biomedical research.
Such software is referred to as scientific or research software,
and represents the following general characteristics:

- smaller audiences (number of users) than other open source projects
- developers and users are associated with academia
- developers and contributors are often not primarily software engineers, but biologists
- funding is derived primarily from grants

While these characteristics are not absolute across scientific research software,
they do present certain challenges,
and may render more general resources for open source software inapplicable.
Such caveats are referenced when resources listed may not be specifically catered towards research software engineering.

For more information on how scientific (academic) software fits into the landscape of open source,
please see [Sectoring contributions to open source software (OSS) on GitHub](https://dspg-young-scholars-program.github.io/dspg20oss/?dspg). 
For a general overview of considerations in developing research software, 
please see [Ten Simple Rules for the Open Development of Scientific Software](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002802).

## Project management for research software

[Project management](https://www.usability.gov/what-and-why/project-management.html) in a general sense refers to planning and organizing a project.
Additionall, there are multiple [formal project management frameworks](https://asana.com/resources/project-management-methodologies),
such as Agile, Waterfall, and Scrum,
that provide structure and language around both team interactions and the software development process.

This section will focus on project management in a more general sense,
including specific approaches that support open science projects throughout their life cycles.

### Planning for sustainability

The Software Sustainability Institute (SSI) has a number of [resources](https://www.software.ac.uk/resources) 
specifically catered to planning and assessing longevity in scientific software:

- [Software management plan](https://www.software.ac.uk/resources/guides/software-management-plans)
- [Software Evaluation Guide](https://www.software.ac.uk/resources/guides-everything/software-evaluation-guide)

The success of general open source tools reveals the following ideas about monetization,
though the [caveats about scientific software mentioned above](#research-software-as-a-subset-of-open-source-software)
are especially applicable here:

- [Monetizing Open Source: Business Models That Generate Billions](https://www.forbes.com/sites/glennsolomon/2020/09/15/monetizing-open-source-business-models-that-generate-billions/?sh=769ff83834fd)
- [4 successful open source business models to consider](https://opensource.com/article/17/12/open-source-business-models)

There are three main sources of funding commonly used to support academic/scientific research software:

- **Grant funding:** federal agencies and non-profit organizations periodically offer opportunities to support open source software
- **Private donations:** a number of options are available for soliciting and accepting small donations from private groups: [GitHub sponsorship](https://github.com/sponsors), [Experiment](https://experiment.com/), [Open Collective](https://opencollective.com/)
- **Services:** offering training or consulting associated with the software can provide a nominal level of support for the software at the core of the project

### Governance

Governance refers to the rules and policies that dictate how decisions are made 
and power controlled within a group.
The larger a community, the more important clearly stated governance is to cultivating and maintaining cohesiveness among programs.

The following resources provide a general overview of themes within governance and leadership 
that members of the scientific open source community recommend for background information
and to highlight the importance of governance:

- [The Tyranny of Structurelessness](https://www.jofreeman.com/joreen/tyranny.htm), an article that describes the challenges associated with organizations that lack formal governance
- [Exploring community governance models](https://www.cscce.org/2021/11/19/novembers-community-call-recap-exploring-community-governance-models/), a blog post describing discussion from a community call for CSCCE
- [Sociocracy](https://www.sociocracyforall.org/sociocracy/), an in-depth description of a governance system well-suited to self-governing organizations based on a value of equality

These resources are useful for developing and applying models of governance for your own project:

- [CommunityRule](https://communityrule.info/), a governance toolkit for a wide variety of community organizations
- [A guide to open source project governance models](https://www.redhat.com/en/resources/guide-to-open-source-project-governance-models-overview) from RedHat
- [Leadership and Governance](https://opensource.guide/leadership-and-governance/) from Open Source Guides
- [GitHub's Minimum Viable Governance](https://github.com/github/MVG)

Finally, here are some examples of governance documentation in open source communities.
These were selected because they represent a variety of projects and structures:

- [The Carpentries Governance](https://carpentries.org/governance/)
- [Project Jupyter](https://github.com/jupyter/governance/blob/master/governance.md)
- [`ggplot2`](https://github.com/tidyverse/ggplot2/blob/main/GOVERNANCE.md), an R package
- [`numpy`](https://numpy.org/doc/stable/dev/governance/governance.html#governance), a Python package

### Team management

**Under construction**

While governance refers to how an entire project operates,
team management refers to coordination among the core members working on a project.
For an overview of working in a team for scientific projects, 
see [Strategies for Team Science Success](https://link.springer.com/book/10.1007/978-3-030-20992-6).

For an example of public documentation about an open source project,
view the [2i2c Team Compass](https://team-compass.2i2c.org/en/latest/).

### Code review

**Under construction**

## Community development

The rest of the content on this page focuses on developing communities of researchers involved in your project,
which includes both contributors to and users of your software.
The following resources provide an overview of communities related to open source software,
including ways to consider cultivating a community:

- [CSCCE Community Profiles](https://www.cscce.org/resources/scientific-community-profiles/)
- [Community starter kit](https://lab.github.com/githubtraining/community-starter-kit) from GitHub
- [The Labor of Maintaining and Scaling Free and Open-Source Software Projects](https://stuartgeiger.com/articles/2021-02-28-maintaining-scaling-foss-cscw2021/)

### Diverse, equitable, and inclusive communities

An assumption for all resources presented here is that the communities are diverse,
representing a wide variety of demographics among many different axes of variation,
equitable, meaning everyone has the opportunity to participate,
and inclusive, in that everyone feels welcome to participate.
While this assumption is implicit for all sections of this informational website,
the following sections in other parts of this site explicitly discuss resources related to inclusive software and community development:

- [Code of Conduct](#code-of-conduct)
- [Tracking project metrics](#tracking-project-metrics)
- [Accessibility](/open-science/code/code-development#user-interfaces)
- [Organizations involved in DEI](/open-science/resources/organizations)

The following resources discuss specific efforts on the part of open source projects to address such issues:

- [Addressing Diversity, Equity, and Inclusion in 2021 and Beyond](https://www.linuxfoundation.org/blog/addressing-diversity-equity-and-inclusion-in-2021-and-beyond/) from the Linux Foundation

### Code of conduct

A Code of Conduct (CoC) clearly identifies expectations of behavior associated with a project and/or event.
In addition to stating what is (and is not) allowed,
CoCs inform participants how to report violations of behavior,
as well as identify the process associated with handling such reports.

The [Contributor Covenant](https://www.contributor-covenant.org/)
is a CoC that has been adopted and applied by many open source projects.
The [most recent version](https://www.contributor-covenant.org/version/2/1/code_of_conduct/)
includes standard processes for enforcing CoCs.

Additional examples of CoCs include:

- [CZI Community Participation Guidelines](https://chanzuckerberg.com/ethics-policies/community-participation-guidelines/)
- [R-Ladies Global Code of Conduct](https://rladies.org/code-of-conduct/)
- [The Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html)

For more information about how CoCs are used in open source,
see [Code of Conduct Conversations in Open Source Software Projects on Github](https://dl.acm.org/doi/10.1145/3449093).

### Contribution guidelines

Inviting and recruiting individuals to contribute to an open source project is challenging
yet critical for the long-term success of the project.
Contribution guidelines provide the basic information such individuals require
to consider, and hopefully even follow through,
with sharing work.

These resources provide guidance on developing contribution guidelines for open source projects:

- [Ten simple rules for helping newcomers become contributors to open projects](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007296)
- [A template for creating open source contributor guidelines](https://opensource.com/life/16/3/contributor-guidelines-template-and-tips)
- [Write Contributor Guidelines ](https://mozilla.github.io/open-leadership-training-series/articles/building-communities-of-contributors/write-contributor-guidelines/) from Mozilla's Leadership Training Series

The resources above are for traditional open source projects.
It is likely that individuals interested in contributing to a project
may not have the technical expertise or amount of time available to commit as described.
The following table is adapted from [Call for Code](https://callforcode.org/),
and identifies different types of contributions possible with variable amounts of time:

| Time commitment | Documentation | Design | Advocacy | Community |
|---|---|---|---|---|
| Hours | Flag documentation errors or questions | Design logo | Share project in communities | Attend community event |
| Days | Document new features | Conduct user research | Speak at conference | Organize community event |
| Weeks | Create onboarding guides | Update UI | Be a project champion | Lead regional chapter |

Examples of contribution guidelines include:

- [The Carpentries](https://github.com/swcarpentry/python-novice-inflammation/blob/gh-pages/CONTRIBUTING.md)
- [Tidyverse](https://www.tidyverse.org/contribute/)
- [GitHub Pages Minimal theme](https://github.com/pages-themes/minimal/blob/master/docs/CONTRIBUTING.md) 

### Tutorials and other user support

Basic user documentation is described in the [Documentation section of the Code development page](/open-science/code/code-development#documentation).
User support can also include a variety of tutorials and other types of training support.
The following resources are useful starting points for anyone interested in 
developing training materials associated with their open source projects:

- [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org/)
- [Ten Simple Rules for Developing a Short Bioinformatics Training Course](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002245)
- [Ten simple rules for delivering live distance training in bioinformatics across the globe using webinars](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006419)
- [Ten Simple Rules for Providing a Scientific Web Resource](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1001126)
- [Ten simple rules for collaborative lesson development](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005963)

### Tracking project metrics

Collecting and sharing information about an open source project is another important part of the growth and development of software engineering,
as it demonstrates the community support (and therefore longevity) of a project.
The following resources describe the types of information appropriate to collect for open source projects:

- [Community Health Analytics Open Source Software (CHAOSS)](https://chaoss.community/)
- [Open Source Software Needs Assessment Toolkit](https://internews.org/areas-of-expertise/global-tech/resources/open-source-software-lightweight-needs-assessment/)
- [Apache project maturity model](http://community.apache.org/apache-way/apache-project-maturity-model.html)

If you are interested in tracking the demographics of participants in your project and are unsure how to approach questions related to diversity, equity, and inclusion, 
please see [Open Demographics](http://nikkistevens.com/open-demographics/).

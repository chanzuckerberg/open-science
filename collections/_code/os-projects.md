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
  - [Creating user documentation](#creating-user-documentation)
  - [Short training courses](#short-training-courses)
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

FIXME

[Resources from the Software Sustainability Institute](https://www.software.ac.uk/resources):

- [Software management plan](https://www.software.ac.uk/resources/guides/software-management-plans)
- [Software Evaluation Guide](https://www.software.ac.uk/resources/guides-everything/software-evaluation-guide)

Resources on financial models for general open source tools:

- [Monetizing Open Source: Business Models That Generate Billions](https://www.forbes.com/sites/glennsolomon/2020/09/15/monetizing-open-source-business-models-that-generate-billions/?sh=769ff83834fd)
- [4 successful open source business models to consider](https://opensource.com/article/17/12/open-source-business-models)

Revenue models:

- Private donations: GitHub sponsorship, [Experiment](https://experiment.com/), [Open Collective](https://opencollective.com/)
- Service models: offering training or consulting for a fee

Making the case for funding:

- see tracking metrics section

### Governance

FIXME

- [The Tyranny of Structurelessness](https://www.jofreeman.com/joreen/tyranny.htm)
- CommunityRule https://communityrule.info/
- Sociocracy – basic concepts and principles https://www.sociocracyforall.org/sociocracy/

### Team management

FIXME

- onboarding/offboarding, and hiring/firing
- https://team-compass.2i2c.org/en/latest/
- [Strategies for Team Science Success](https://link.springer.com/book/10.1007/978-3-030-20992-6)

### Code review

**Under construction**

## Community development

FIXME

- [CSCCE Community Profiles](https://www.cscce.org/resources/scientific-community-profiles/)
- [Community starter kit](https://lab.github.com/githubtraining/community-starter-kit) from GitHub
- [The Labor of Maintaining and Scaling Free and Open-Source Software Projects](https://stuartgeiger.com/articles/2021-02-28-maintaining-scaling-foss-cscw2021/)

### Diverse, equitable, and inclusive communities

FIXME
Everything is about DEI

- [CoC](#code-of-conduct)
- [Tracking project metrics](#tracking-project-metrics)
- [Accessibility](/open-science/code/code-development/#user-interfaces)
- [Organizations involved in DEI](/open-science/resources/organizations)

### Code of conduct

FIXME

- Code of Conduct
  - expectations for behavior
  - reporting
  - process for resolving
- Code of Conduct Conversations in Open Source Software Projects on Github https://dl.acm.org/doi/10.1145/3449093

### Contribution guidelines

FIXME

- [Ten simple rules for helping newcomers become contributors to open projects](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007296)
- https://opensource.com/life/16/3/contributor-guidelines-template-and-tips
- https://mozilla.github.io/open-leadership-training-series/articles/building-communities-of-contributors/write-contributor-guidelines/

Examples:

- https://github.com/swcarpentry/python-novice-inflammation/blob/gh-pages/CONTRIBUTING.md

Non-technical contributions

Adapted from [Call for Code](https://callforcode.org/)

| Time commitment | Documentation | Design | Advocacy | Community |
|---|---|---|---|---|
| Hours | Flag documentation errors or questions | Design logo | Share project in communities | Attend community event |
| Days | Document new features | Conduct user research | Speak at conference | Organize community event |
| Weeks | Create onboarding guides | Update UI | Be a project champion | Lead regional chapter |

### Creating user documentation

FIXME
link to documentation in code-development

- [Ten Simple Rules for Providing a Scientific Web Resource](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1001126)
- [Ten simple rules for collaborative lesson development](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005963)
- [The Types, Roles, and Practices of Documentation in Data Analytics Open Source Software Libraries: A Collaborative Ethnography of Documentation Work](https://stuartgeiger.com/articles/2018-05-28-cscw-documentation/)

### Short training courses

The following resources are useful starting points for anyone interested in 
developing training materials associated with their open source projects:

- [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org/)
- [Ten Simple Rules for Developing a Short Bioinformatics Training Course](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002245)
- [Ten simple rules for delivering live distance training in bioinformatics across the globe using webinars](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006419)

### Tracking project metrics

FIXME

- attribution
- incentivization

- [Community Health Analytics Open Source Software (CHAOSS)](https://chaoss.community/)
- [Open Source Software Needs Assessment Toolkit](https://internews.org/areas-of-expertise/global-tech/resources/open-source-software-lightweight-needs-assessment/)
- [Apache project maturity model](http://community.apache.org/apache-way/apache-project-maturity-model.html)

- Tracking DEI metrics
  - [Open Demographics](http://nikkistevens.com/open-demographics/), [GitHub repo](https://github.com/drnikki/open-demographics/)

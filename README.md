# Open Science Research Resources

## About this project

This repository houses the code and content for [this website](https://chanzuckerberg.github.io/open-science/)
of resources.

> All CZI Science activities became a part of Biohub in November 2025. 
> Although some materials linked here may still reference CZI,
> we are gradually updating this language to Biohub.

![Essential Open Source Software for Science](https://img.shields.io/badge/EOSS-FF414B.svg?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSI0NSIgaGVpZ2h0PSI0NSI+PHBhdGggZD0iTTIyLjA5OCAyMS4wNzRjLTEuMjM1Ljg2LTIuNjggMS4zOTktNC42ODggMS40MzgtMi40MjYuMDUtNC4yMzgtMS41NTEtNC40MDYtMy45MThhNC40NjUgNC40NjUgMCAwIDEgMS4xODctMy4zOCA0LjQ4IDQuNDggMCAwIDEgMy4yODYtMS40NDQgNC42NzQgNC42NzQgMCAwIDEgMS44OTQuMzc1cy0uMTU2IDEuMzItLjIxIDEuOTE0bDEuOTg3LjAxNS4zNTYtMi45NzYtLjU2My0uMzU2YTYuNTQxIDYuNTQxIDAgMCAwLTMuNDg0LS45NjkgNi41OTMgNi41OTMgMCAwIDAtNC43NSAyLjA4NiA2LjQxNSA2LjQxNSAwIDAgMC0xLjcxNSA0Ljg3NWMuMTEzIDEuNjEuODA5IDMuMDc4IDEuOTUgNC4xNDEgMS4xNTYgMS4wNyAyLjcxNCAxLjY0NSA0LjM5OCAxLjYzMy4wMzkgMCAuMDc4IDAgLjEyNS0uMDA0YTkuOTE4IDkuOTE4IDAgMCAwIDMuNDMzLS43MjNsMS40MzQtMi43ODlzLS4wMjctLjA2Mi0uMjM0LjA3OCIgc3R5bGU9InN0cm9rZTpub25lO2ZpbGwtcnVsZTpub256ZXJvO2ZpbGw6I2ZmZjtmaWxsLW9wYWNpdHk6MSIvPjxwYXRoIGQ9Im0yOC44NjMgMjguMjE1LS4yNDIgMi43NDJ2LjAzMWMtLjEwMSAxLjAzNS0uNjUyIDEuOTE0LTEuNDg0IDIuMzUyLS42Ni4zNDctMS4zOC4zNDctMi4wMjgtLjAwOC0uNjc1LS4zNjMtLjk5Mi0uOTE4LTEuMTE3LTEuNjEzLS4xODctMS4xMDIuNDM4LTIuMjU0IDEuMjkzLTIuODMybDEzLjM1Mi04LjY4OGMuMDk3LjczOC4xNTIgMS40ODUuMTUyIDIuMjUgMCA4Ljk5Mi03LjMwOSAxNi4zMDUtMTYuMjkzIDE2LjMwNS04Ljk4OCAwLTE2LjI4OS03LjMxMy0xNi4yODktMTYuMzA1IDAtOC45ODggNy4zMDUtMTYuMyAxNi4yOTMtMTYuM3MxMi40OTYgNC4wOSAxNC45ODQgOS45MUwzOS4xMTQgMTVDMzYuMjYxIDguNjY0IDI5Ljg5MyA0LjIzNCAyMi41IDQuMjM0Yy03LjM5NSAwLTE4LjIxNSA4LjE3Mi0xOC4yMTUgMTguMjE1IDAgMTAuMDQ3IDguMTcyIDE4LjIxMSAxOC4yMTEgMTguMjExIDEwLjA0IDAgMTguMjE1LTguMTcyIDE4LjIxNS0xOC4yMSAwLTEwLjA0LS4xMS0yLjI5NC0uMzEzLTMuMzkxYTE5Ljk5NyAxOS45OTcgMCAwIDAtLjQ1My0xLjgzMmwtMy43OTMgMi4zNy01LjAyIDMuMThjLS4xNzUtLjY2OC0uNTgxLTEuMzQzLTEuNDQtMS43My0xLjAxMi0uNDY1LTIuNjYtLjExLTMuODY4LjU4MiAwIDAgMy4zMDUtNi40MDIgMy44Ni03LjQ1LjAzNS0uMDY2LS4wMTYtLjE0OC0uMDk4LS4xNDhoLTYuMThsLS4yNSAyLjA2N0gyNi41MDhsLTQuNzMgOS4wNjJjLS4wOTQuMTc2LjA5Ny4zNjMuMjc3LjI3NGwyLjUyMy0xLjM0YzEuMjE5LS42MjUgMy4yNS0xLjkxIDQuMjU0LTEuMTY4LjE0NS4xMS4zMzIuMzk4LjM0OC42OTVhLjM1Ny4zNTcgMCAwIDEtLjE0OS4yOTNsLTUuMDQzIDMuNDA2Yy0xLjYzNiAxLjE2OC0yLjI3NyAyLjkxLTIuMTIgNC41NTUuMTI0IDEuMzc1Ljk4NCAyLjU2NiAyLjI1NyAzLjI2MmE0LjE3IDQuMTcgMCAwIDAgMi4xMTMuNTE1IDQuMTY5IDQuMTY5IDAgMCAwIDEuODY0LS41YzEuNDM3LS43NTQgMi4zOTQtMi4yMzQgMi41NjItMy45NDVsLjQwMi00LjYxMy0yLjE5OSAxLjYzM1ptMCAwIiBzdHlsZT0ic3Ryb2tlOm5vbmU7ZmlsbC1ydWxlOm5vbnplcm87ZmlsbDojZmZmO2ZpbGwtb3BhY2l0eToxIi8+PC9zdmc+)
Are you an EOSS grantee? [Go here](https://chanzuckerberg.github.io/open-science/eoss-grantees#acknowledging-czi)
to learn about different options for adding an EOSS badge to your software project page.

## Code of Conduct

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-baaaa.svg)](CODE_OF_CONDUCT.md)

This project adheres to the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code.
Please report unacceptable behavior to <opensource@chanzuckerberg.com>.
For more information on the Contributor Covenant,
please [visit their website](https://www.contributor-covenant.org/).

## Project status and governance

This project is currently led by the Open Science Program Office (OSPO)
at [Biohub](https://biohub.org/).
The website is currently actively maintained;
[open issues](https://github.com/chanzuckerberg/open-science/issues)
track upcoming tasks to be completed.
For more information on how decisions are made regarding this project,
please see our [Governance documentation](https://chanzuckerberg.github.io/open-science/GOVERNANCE).

## Contributing to this project

If you would like to request content or contribute code and/or information for us to share via this project,
please see our [Contribution guidelines](https://chanzuckerberg.github.io/open-science/CONTRIBUTING/).

## Reporting security issues

If you believe you have found a security issue,
please responsibly disclose by contacting us at <security@chanzuckerberg.com>.

## Acknowledgements

This website is created using [jekyll](https://jekyllrb.com/)
and the [minimal theme](https://github.com/pages-themes/minimal),
with hosting through [GitHub Pages](https://pages.github.com/).
The website search function uses [lunr.js](https://lunrjs.com/),
implemented as described by [Jekyll Codex](https://jekyllcodex.org/without-plugin/search-lunr/#)

In addition to supporting the backbone of this website,
many thanks to the [minimal theme](https://github.com/pages-themes/minimal)
for providing excellent reference material for our Contribution guidelines.

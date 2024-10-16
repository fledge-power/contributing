# Contributing to FledgePower

The project welcomes contributions of all types; documentation, code changes, new plugins, scripts, just simply reports of the way you use FledgePower or suggestions of features you would like to see within FledgePower.

The following is a set of guidelines for contributing to the FledgePower project. These are mostly guidelines, sometimes rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[License and Developer Certificate of Origin](#license-and-developer-certificate-of-origin)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs and Suggesting Enhancements](#reporting-bugs-and-suggesting-enhancements)
  * [Contributing Code](#contributing-code)
  * [Definition of Done](#definition-of-done)

[Styleguides](#styleguides)
  * [Git Commit Messages](#git-commit-messages)
  * [English language convention](#english-language-convention)

[Project Governance](#project-governance)
  * [Project Owner](#project-owner)
  * [Technical Charter](#technical-charter)
  * [Committers](#committers)
  * [Technical Steering Committee](#technical-steering-committee)
  * [Contributors](#contributors)

## Code of Conduct

This project applies the [LF Energy Code of Conduct](https://www.lfenergy.org/about/code-of-conduct/). By participating, you are expected to uphold this code. Please report unacceptable behavior to the project's Technical Steering Committee [fledgepower-tsc@lists.lfenergy.org](mailto:fledgepower-tsc@lists.lfenergy.org).

## License and Developer Certificate of Origin

By contributing to the FledgePower project, you accept and agree to the following terms and conditions for your present and future contributions submitted to FledgePower.

All contributions to this project are licensed under the license stipulated at the corresponding sub-repository. Except where otherwise explicitely indicated, FledgePower is an open source project licensed under the [Apache License, version 2.0](http://www.apache.org/licenses/LICENSE-2.0/). 

The project requires the use of the [Developer Certificate of Origin (DCO)](https://developercertificate.org/). The DCO is a legally binding statement asserting that you are you have the right to submit your contribution and to license it under the project's applicable license.

Contributors sign-off that they adhere to the term of the DCO by adding a ``Signed-off-by`` line to commit messages. The DCO sign-off must be attached to every contribution made by every contributor.

Here is an example ``Signed-off-by`` line, that indicates the contributor accepts the DCO:

````
This is my commit message.

Signed-off-by: Name Surname <name.surname@entity.com>
````
You can write it manually but Git even has a -s command line option to append this automatically to your commit message:
````
$ git commit -s -m 'This is my commit message'
````

Note that checks will be performed during the integration in order to require that commits in a Pull Request contain valid ``Signed-off-by`` lines.

## How Can I Contribute?

### Reporting Bugs and Suggesting Enhancements

Bugs and enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). Create an issue and provide the following information by filling in the template.

Before creating bug reports or suggesting enhancement, please **perform a [cursory search](https://github.com/search?q=+is%3Aissue+user%3Acom-pas)** to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one..

If you find a security vulnerability then we request that you inform us via email at [fledgepower-tsc@lists.lfenergy.org](mailto:fledgepower-tsc@lists.lfenergy.org) rather than by opening an issue in GitHub. This allows us to act on it without giving information that others might exploit. Any security vulnerability will be discussed at the project TCS and user will be informed of the need to upgrade via the Fledge slack channel.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

### Contributing Code

Code Contribution is tracked as [GitHub Pull Requests](https://help.github.com/en/articles/about-pull-requests). Crafting a good pull request takes time and energy and we will help as much as we can, but be prepared to follow our iterative process. The iterative process has several goals:

- maintain the software quality,
- fix problems that are important to users,
- engage the community in working toward the best possible software features,
- enable a sustainable system for maintainers to review contributions.

### Definition of Done

Before finishing a requirement, you need to check if everything is done for that particular requirement.
For that, we have a Definition of Done; the DoD decides when a requirement is really done.

Note: A Defintion of Done is not a static list. It can be modified any time, if people feel like corrections should be made.

Current Definition of Done:
- Assumptions of requirements are met.
- Required documentation is done.
- (Software) Requirement is accepted and got a thumbs up from the Maintainer via an accepted Pull Request.
- (Software) The build succeeds without failures.
- (Software) All tests in the test suite pass.
- (Software) Code style checks report no violations.
- (Software) Code coverage is high enough (a minimum of 80% is coveraged).
- (Software) If applicable, the added Unit Test is written, executed and passed.
- (Software) Security analysis (vulnerability detection) doesn't spot unaddressed issues.

## Styleguides

### Git Commit Messages

As usual, please start the commit message with a short line describing the commit, then leave a blank line, then give more context and explanations. You can use GitHub's integrations, for exemple to link to existing issues. In general, pull requests with more than one commits will be squashed when merged in master.

### English language convention

The convention for all the project's documents, including code documentation, website, is to write American English.
A list of spelling differences between British and American English is available 
[here](https://www.britishcouncilfoundation.id/en/english/articles/british-and-american-english) for example.

## Project Governance

#### Project Owner

FledgePower is part of the [LF Energy Foundation](https://www.lfenergy.org/), a project of The Linux Foundation that supports open source innovation projects within the energy and electricity sectors.

#### Technical Charter

The Project's [Technical Charter](FledgePower%20Technical%20Charter%20-%202021-02-11.pdf) sets forth the responsibilities and procedures for technical contribution to, and oversight of, the COMPAS Project.

#### Committers

Committers are contributors who have made several valuable contributions to the project and are now relied upon to both write code directly to the repository and screen the contributions of others. In many cases they are programmers but it is also possible that they contribute in a different role. Typically, a committer will focus on a specific aspect of the project, and will bring a level of expertise and understanding that earns them the respect of the community and the project owner.

Committers/Reviewers: Akli RAHMOUN, Mark RIDDOCH

#### Technical Steering Committee

The Technical Steering Committee (TSC) is composed of voting members elected by the active Committers as described in the project’s Technical Charter. The TSC is responsible for the technical direction of the project.

#### Members
FledgePower TSC voting members are:
- Daniel Lazaro - [Daniel Lazaro | LinkedIn](https://www.linkedin.com/in/daniellazaro/)
- Romain Lebrun Thauront
- Mark Riddoch - [Mark Riddoch | LinkedIn](https://www.linkedin.com/in/mark-riddoch-02ab883/)
- Jakob Vogelsang - [Jakob Vogelsang | LinkedIn](https://www.linkedin.com/in/jakob-vogelsang-235a15181/)

#### Voting
While the Project aims to operate as a consensus-based community, if any TSC decision requires a vote to move the Project forward, the voting members of the TSC will vote on a one vote per voting member basis. The simple majority is needed to approve proposals.

#### Responsibilities
The project is split into several repositories. There is at least one Committer in charge of each repository. By "in charge", we mean:
-	best effort to review the pull request,
-	best effort to resolve issues,
-	building and publishing the releases, including writing the release notes and informing the community,
-	in case of unability to perform the above tasks, the Committer in charge has to ask the TSC through the list [fledgepower-tsc@lists.lfenergy.org](mailto:fledgepower-tsc@lists.lfenergy.org) to find another Committer to review the pull request, resolve the issue or build and publish the release.

#### Contributors

Contributors include anyone in the technical community that contributes code, documentation, or other technical artifacts to the Project.

Anyone can become a contributor. There is no expectation of commitment to the project, no specific skill requirements and no selection process. To become a contributor, a community member simply has to perform one or more actions that are beneficial to the project.

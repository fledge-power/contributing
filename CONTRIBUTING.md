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

# Contributing

The purpose of this guide is to help you contribute to Opt Out Tools, 
regardless of your skill level or amount of time you are able to contribute.

Quick links:

- [How much time do you have?](#How-much-time-do-you-have?)
- [Project Management](#Project-Management)
- [Feature Request/Bug Report](#Feature-Request/Bug-Report)
- [Contributing Code](#Feature-Implementation---Contributing-Code)
- [Non Code Contributions](#Non-Code-Contributions)
- [Code of Conduct](#Code-of-Conduct)


## How much time do you have?
### Less 10 minutes
 - Talk to a friend about online misogyny and what Opt Out Tools are trying to 
achieve
 - Protest online about the abuse female-identifying people are receiving
 - Talk to us on slack about bright ideas you have for new/better 
functionality (to get an invite reach out at @OptOutSocial)
 
### Less 30 minutes
 - Look through the open issues for a problem that is small and sweet to fix
 - Post/tell lots of people about the issue and about Opt Out Tools! Use our 
Twitter handle @OptOutSocial

### Programming (1+ hours)

Take a look through the open issues and then check with pull requests to make 
sure that someone isn't already working on it. Please post in an issue to say 
that you're working on it.

If you are making a substantial or potentially controversial change, your 
first port of call should be to stop by and chat to us on Slack or file an 
issue to discuss what you would like to change. We really don't want you to 
waste time on a pull request (GitHub jargon for a contribution) that has no 
chance of being merged.

If you have no tests, your code won't be merged. We're aiming for 100% test 
coverage.

## Project Management
Opt Out Tools is a multifaceted organisation and because of this it has both 
containing code and non code containing repos. We use the Github projects 
board to organise our multifaceted work. We have different projects that are 
for specific pieces of work as well as Roadmaps that give people an overview. 
These projects will contain all the work related to that piece of work, it can 
thus contain work that spans multiple repos.

We use Github issues to create, discuss or carry out work. Each issue can take 
one of three forms, a either a bug, a feature request or feature 
implementation (task). 

- Bug: a problem with the code that needs fixing
- Feature request: an idea for new features
- Feature implementation: concrete steps to be completed to add the 
feature/fix the bug

Bug and feature requests become feature implementations when someone has a 
brainwave of how to complete the task. Thus a feature implementation issue 
will contain clear instructions of how to complete task.

Each issue should be labeled with a minimum of two labels, one to indicate 
priority and the second to indicate size of task. It should also belong to a 
milestone. We have four milestones over the next months, which look like this:

Milestone name and description:

- 0.1: the minimum viable product (MVP), what is the minimum functionality our 
tool/s can have to be ready
- 0.2: what is then expected by the end user for the tool/s to have
- 0.3: what features would be good to have in the tool/s
- 0.4: the future of our tool/s

Concrete details of what each milestone contains can be found in the tool's 
roadmap. For example, to see what we want to achieve in terms of Activism by 
the 0.1 milestone, see the [Activism 
Roadmap](https://github.com/orgs/opt-out-tools/projects/37)

To find out what tools we have, please see [Our Tools and Our 
Vision](https://github.com/opt-out-tools/start-here#Our-Tools-and-Our-Vision). 
An overview of tasks for each milestone can be found 
[here](https://github.com/opt-out-tools/start-her#Tools-Roadmap).

Each issue should belong to a step in the Roadmap which will then be sorted
into a project.

Issues may have two kinds of squared bracket labels in the title:
- [WIP]: indicate you are working on something to avoid duplicated work, 
request broad review of functionality or API, or seek collaborators (use the 
help wanted label).
- [MRG]: the contribution is complete and should be subjected to a detailed 
review


## Feature Request/Bug Report
We use GitHub issues to track all bugs and feature requests; feel free to open 
an issue if you have found a bug or wish to request a feature.

In case you experience issues using any repo, do not hesitate to submit a 
ticket to the Bug Tracker of the relevant repo. You are also welcome to post 
feature requests or pull requests.

It is recommended to check that your issue complies with the following rules 
before submitting:

    Verify that your issue is not being currently addressed by other issues or 
pull requests.
    
    If you are submitting a bug report, we strongly encourage you to follow 
the guidelines in How to make a good Bug Report.

### How to write a good Bug Report
When you submit an issue to Github, please do your best to follow these 
guidelines! This will make it a lot easier to provide you with good feedback:

    The ideal bug report contains a short reproducible code snippet, this way 
anyone can try to reproduce the bug easily (see this for more details). If 
your snippet is longer than around 50 lines, please link to a gist or a github 
repo.

    If not feasible to include a reproducible snippet, please be specific 
about what models, data and functions that are involved.

    If an exception is raised, please provide the full traceback.

    Please include your operating system type and version number, as well as 
your laguage (python, javacript) version and other important packages such as 
scikit-learn, numpy, and scipy.

### How to write a good Feature Request
When submitting a feature request, please try and:
    
    As clear as possible
    
    Contain relevant documentation wireframes etc. 

## Feature Implementation - Contributing Code
Feature requests and bug fixes become a feature implementation issue when 
anyone has a eureka moment. The aim of the feaure implementation issue is to 
identify the steps to complete the feature/fix. This is done to help the less 
confident pick up tasks and get clear stpes on how to complete a PR.

When you've found a feature to implement and are ready to contribute to a 
repo, then begin by forking it on GitHub, then submit a “pull request” 
(PR).

The first few steps are generic to all Opt Out Tools repos and involves 
setting up your git repository:

    Create an account on GitHub if you do not already have one.

    Fork the project repo: click on the ‘Fork’ button near the top of the 
page. This creates a copy of the code under your account on the GitHub user 
account. For more details on how to fork a repository see 
https://help.github.com/en/github/getting-started-with-github/fork-a-repo

    Clone your fork of the repo from your GitHub account to your local disk

Once these steps are complete please see the individual README.md for specific 
installation details.

### Pull Request Checklist
Before a PR can be merged, it needs to be approved by one core developer. 
Please prefix the title of your pull request with [MRG] if the contribution is 
complete and should be subjected to a detailed review. An incomplete 
contribution – where you expect to do more work before receiving a full 
review – should be prefixed [WIP] (to indicate a work in progress) and 
changed to [MRG] when it matures. For a more detailed explanation of what 
these mean to the organisation please see [Project 
Management](#Project-Management)

In order to ease the reviewing process, we recommend that your contribution 
complies with the following rules before marking a PR as [MRG]. The bolded 
ones are especially important:

- Give your pull request a helpful title that summarises what your 
contribution does. This title will often become the commit message once merged 
so it should summarise your contribution. In some cases “Fix <ISSUE 
TITLE>” is enough. “Fix #<ISSUE NUMBER>” is never a good title.
- Make sure your code passes the tests.
- Make sure your code is properly commented and documented, and make sure the 
documentation renders properly
- Tests are necessary for enhancements to be accepted. 
- Make sure that your PR does not add any linter violations.


Follow the Coding guidelines.

    When applicable, use the validation tools and scripts.

    Often pull requests resolve one or more other issues (or pull requests). 
If merging your pull request means that some other issues/PRs should be 
closed, you should use keywords to create link to them (e.g., Fixes #1234; 
multiple issues/PRs are allowed as long as each one is preceded by a keyword). 
Upon merging, those issues/PRs will automatically be closed by GitHub. If your 
pull request is simply related to some other issues/PRs, create a link to them 
without using the keywords (e.g., See also #1234).

    New features often need to be illustrated with narrative documentation in 
the user guide, with small code snipets. If relevant, please also add 
references in the literature, with PDF links when possible.


### CI/CD

We have Circle CI in two of our code repos.

### Branch Naming Convention
We use a branch for each major release, and tags on that branch for each
 minor release.

For example, beta users will use a beta or a release candidate, which will 
have a 0.2beta1 release name and tag on the 0.2.X branch. 


## Contributing Anything Other than Code
Non code contributions are vital to this project. All that we require is
interest and initiative, we will have missed bits or not included something
and we welcome the community to actively fill in those gaps

A non-exhaustive list of potential non-code contributions include:

- Star the [opt-out](https://github.com/opt-out-tools/opt-out) repo
- Tweet about our great work @OptOutSocial
- Add to our research: feminist, data science, policy, design
- Help develop our workshops
- Write content for the campaign or website

The last three points lead me on to talk about another huge part of our work, 
our wiki's. This is how we store and share our knowledge across the team.

### Wiki


## Code of Conduct

> Please note that this project is released with a [Contributor Code of 
Conduct](https://github.com/malteserteresa/opt-out/blob/master/CODE_OF_CONDUCT.
md). By participating in this project you agree to abide by its terms.

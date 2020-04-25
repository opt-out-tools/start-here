<p align="center"> <img width="250" height="250" src="opt_out_logo.png"> </p>

<p></p> <h1 align="center"> Opt Out Tools </h1>

<h2 align="center"> We are building tools to hide online misogyny and help
 women engage with healthy online discussion </h2>

<p align="center"> <img src="opt-out-demo.gif"> </p>

# Opt Out Tools

Welcome to the **Opt Out Tools (OOT)** project. This repository contains
information about our project and the way we work, as well as general
instructions to help you contribute to the project in any way you can.

Quick links:

- [Repository purpose](#Repository-purpose)
- [Repository-structure](#Repository-structure)
- [Repository-management](#Repository-management)
- [Code of conduct](#Code-of-conduct)
- [Disclaimer](#Disclaimer)

## Repository purpose

This repository

## Repository structure

## Repository management

## Code of conduct

Please note that this project is released with a [Contributor Code of Conduct](https://github.com/malteserteresa/opt-out/blob/master/CODE_OF_CONDUCT.md).
By participating in this project you agree to abide by its terms.

## Disclaimer

Our intention is to **never ever** re-victimize anyone. However we deal with
explicit content and sometimes we forget to sanitize a work or add a disclaimer
that it may content explicit content. If this happens, please let us know and
we'll rectify the matter immediately.

<p align="center"> * * * </p>







# The Repos and their Roles
An overview of the repositories we have an what they are there for

- [opt-out](https://github.com/opt-out-tools/opt-out): the front-end for the
  browser extension
- [website](https://github.com/opt-out-tools/website): the front-end for the
  website
- [public_api](https://github.com/opt-out-tools/public_api): the joint back-end
  for the website and browser extension
- [theory-of-online-misogyny](https://github.com/opt-out-tools/theory-of-online-misogyny):
  qualitative research into online misogyny
- [study-online-misogyny](https://github.com/opt-out-tools/study-online-misogyny):
  quantitative research into online misogyny

<p align="center"> * * * </p>

# Use Our Tools
## Browser Extension

Our browser extension works only on Firefox. The code to load the browser
extension can be found in [opt-out](https://github.com/opt-out-tools/opt-out).

To use the current version:
1. Clone a local copy of the master branch of the [extension
   repo](https://github.com/opt-out-tools/opt-out)
2. Start Mozilla Firefox (make sure you have the latest installed v69.0 at
   least)
3. Set the url to `about:debugging#/runtime/this-firefox` and hit enter
4. In the `Load Teporary Add-ons` box, open and load `manifest.json` which can
   be found in the `extensions` folder of this repo you cloned locally
5. Open Twitter and test!
6. If you make changes to the code you would like to test, make sure you click
   "reload" (left of the "remove" button) to apply new changes to script

## Study Online Misogyny
Look at the
[notebooks](https://github.com/opt-out-tools/study-online-misogyny/tree/master/notebooks)
to see our modeling efforts.

Disclaimer: the data includes harsh and misogynistic statements. Avoid looking
at the data if that's a trigger for you.

## Activism
Our twitter handle is [@OptOutSocail](https://twitter.com/optoutsocial), spread
our message!

## Research
Checkout the [theory of online
misogyny](https://github.com/opt-out-tools/theory-of-online-misogyny) and its
[wiki](https://github.com/opt-out-tools/theory-of-online-misogyny/wiki)

<p align="center"> * * * </p>

# Develop Our Tools
## Status of Repos
Is anything broken?
- [opt-out](https://github.com/opt-out-tools/opt-out):
  [![CircleCI](https://circleci.com/gh/opt-out-tools/opt-out.svg?style=svg)](https://circleci.com/gh/opt-out-tools/opt-out)
- [study-online-misogyny](https://github.com/opt-out-tools/study-online-misogyny):
  [![CircleCI](https://circleci.com/gh/opt-out-tools/study-online-misogyny.svg?style=svg)](https://circleci.com/gh/opt-out-tools/study-online-misogyny)

## The Opt Out Tools Architecture
Here is a diagram depicting the technical architecture of Opt Out Tools.

<p align="center"> <img src="opt_out_architecture.png"> </p>

```
A key:
- square boxes are different repositories
- purple labels are the repository where the code for the component lives
- blue is not implemented yet
- arrows indicate information exchange and flow
```

The browser extension and website share a common back-end called public_api.
Documentation for these two APIs can be find in the
[public_api](https://github.com/opt-out-tools/public_api) repo.

It is important to note that we do not currently have an automated model
deployment mechanism.

## Browser Extension Front-end
The browser extension removes online misogyny from an individual's Twitter
feed. We have a binary classifier model deployed on some servers and as the
page loads the tweets are sent to the backend, the model is hit and returns a
score. If the misogyny score is above the threshold set by the user, the text
is blocked out, if not it’s left on the page. If there is an image attached to
the comment that is also blocked.

Tech stack:
- Javascript

For further details on developing it [click
here](https://github.com/opt-out-tools/opt-out)

## Website Front-end
This is the front-end for our website.
Tech stack:
- Javascript
- Angular 8.0

For further details on developing it [click
here](https://github.com/opt-out-tools/website)

## The Back-end
This has two API's for the website and the browser extension.
Tech stack:
- Python
- Django

For further details on developing it [click
here](https://github.com/opt-out-tools/public_api)

## Modeling
We study online misogyny here. You can find our current work and our future
plans here.

Tech stack:
- Python/R
- Data science (text analytics, network analysis.. etc.)

For further details on developing it [click
here](https://github.com/opt-out-tools/study-online-misogyny)

## Activism & Research
Go to the [theory of online
misogyny](https://github.com/opt-out-tools/theory-of-online-misogyny) and
contribute to the issues or wiki.

<p align="center"> * * * </p>

# Our Organisation

## Teams and Focus
The only thing better than being able to work on a project that really means
something, is being able to work on it with a community of great people.

We have experts from across the world working with a variety of skills from UX
to network analysis. More transparency to come.

<p align="center"> * * * </p>




# Help Our Vision

## Contributing
Opt Out Tools is an open source project under active development. Currently,
machine learning models are being evaluated for their ability to classify
 misogynistic text. If you would like to contribute to the project, please see
the [CONTRIBUTING.md](https://github.com/opt-out-tools/start-here/blob/master/CONTRIBUTING.md)
first, and then check out the CONTRIBUTING.md for the repo you want to work on.

A 5 second contribution can be to :star: the [opt-out
repo](https://github.com/opt-out-tools/opt-out), the more stars we get the more
likely we are to get funding :smile:

## Funding

# Our Mission
We’re a mixed team, including social sciences, UX and lots of data nerds.
We’re all working voluntarily in our spare time to make the internet accessible
for all. What’s most important about us is that we’re a group of people that
**wont let hate win**.

We want to champion female-identifying people back into the online worlds
they’ve been chased out of, support them and their voices whilst still
protecting them and holding the perpetrators accountable. **We need to exist**.

If you share our vision, we ask you to **join us**. Whether it’s by talking
about this to a friend, contributing, research, expertise, skills, strategy or
code. Online misogyny is real and it's silencing the voices that society so
desperately needs to hear.

<h3 align="center"> Let’s Opt Out</h3>

<p align="center"> <img src="built-with-love.png"> </p>

- [1] https://www.theguardian.com/technology/2016/apr/12/the-dark-side-of
-guardian-comments
- [2] https://decoders.amnesty.org/projects/troll-patrol/findings
- [3] https://www.buzzfeednews.com/article/zahrahirji/greta-thunberg-climate-teen-activist-harassment

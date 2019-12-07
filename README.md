<p align="center"> <img width="250" height="250" src="opt_out_logo.png"> </p>

<p></p>
<h1 align="center"> Opt Out Tools </h1>
<h2 align="center"> We are building tools to help female-identifying people engage with healthy online discussion </h2>

<p align="center"> <img src="opt-out-demo.gif"> </p>


Skip to the bit you want to know about

- [Our Tools and Our Vision](#Our-Tools-and-Our-Vision)
- [Tools Roadmap](#Tools-Roadmap)
- [The Repos and their Roles](#The-Repos-and-their-Roles)
- [Use Our Tools](#Use-Our-Tools)
- [Develop Our Tools](#Develop-Our-Tools)
- [Our Organisation](#Our-Organisation)
- [Our Code of Conduct](#Code-of-Conduct)
- [Help us with Our Vision](#Help-Our-Vision)
- [Our Mission](#Our-Mission)

# Our Tools and Our Vision

We currently have five tools we're working on to combat online misogyny. Here's a brief description of each tool:

- **Browser Extension**: works like adBlocker, but removes misogyny instead of adverts
- **Website**: allows an individual to not only support and inform themselves, but submit a report of online misogyny
- **Activism**: saying boo to the misogyny gooses 
- **Research**: understanding online misogyny and the problem domain
- **Modeling**: modeling online misogyny

### Our Browser Extension
Our browser extension is designed to remove misogyny from an individuals social media feed, automatically alerting the moderators of the platform to the detected abuse. However we are consent not censorship focused. We’re designing our browser extension to have a local instance of the model that you can supply feedback to. By giving the individual control over what they do and don’t see whilst upholding their safety, we hope to show female-identifying people that their voices can be heard online without the traumatizing consequences.

### Our Website 
Our website aims to support female-identifying getting their voices back and sustain the movement. Inspired by [HarassMap](https://harassmap.org/ar), an Egyptian based NGO that allows people to submit reports of physical harassment which are displayed online on a map, our website will allow an individual to anonymously submit details of their harassment. This data will be stored, studied and feed the models that our other tools use, for example the browser extension. Our website will transparently show details of the usage statistics of the tools and show female-identifying clearly how their participation by submitting their reports is helping to fuel the movement and show our "antidote to silicon valley KPIs”. Our long-term goal is to display a “virtual” harass map on our website, showing which communities on your selected social media platform are misogynstic or sexually aggressive or just downright abusive, enabling female-identifying to navigate the murky waters of online society as best they can. 

### Our Activism
We’re holding workshops that give female-identifying people a chance to meet and share their experiences online. By doing this we not only give much needed support to these people but allow them to come together and in doing so, act in a form of protest. By helping to form this community, it helps us identify needed technical infrastructure and ensures that our tools are fit for purpose enabling our tech to be as community-driven as possible.

We’re also holding workshops and hackathons to develop our “antidote to silicon valley” KPIs: KPIs that try to measure diversity, inclusivity and health of online conversation. Current metrics of participation such as no. of shares no. of clicks etc. have ensured that the social media tech giants live in the pockets of most people on the planet. But these simple metrics of participation don’t tell the full story. We want to do it differently.

### Our Research
Our tech is here to solve real-world problems. It's vital to us that we compile and understand the latest research around online misogyny to inform our technical decisions. 

Whilst Opt Out's is long-term goal to be able to protect to all female-identifying people one day, we are committed to supporting those who face the most misogyny online. We have found through reviewing academic studies and existing polls that typically, there are a few factors which determine how much abuse a female-identifying people will be subject to online. Firstly, the more publicly visible and outspoken a female-identifying people is, the more likely it is that she will receive online misogyny. We see politicians, academics, journalists (particularly those who write about stereotypically masculine areas like sports and gaming), activists and human rights defenders all receiving gendered abuse online. Many female politicians across Europe are forced to contend with misogyny on a regular basis, sometimes resulting in these politicians stepping down from their positions. If a female-identifying people also happens to be black, trans, obese, any intersecting identity that is already discriminated against, the intensity and amount of abuse increases. We will focus on protecting these voices that disproportionately suffer from online misogyny first and increase inclusivity as we understand how we can model misogyny better.
 
### Our Modeling
Language is incredibly nuanced. Our strategy to build tool that is designed to block misogyny towards a particular group of female-identifying people being harassed online. By initially targeting our protection to a specific group of people, we will ensure that our browser extension is effective from the word go. As we better understand online misogyny and how to model it we will improve our model to have an increased range of groups of people whom our tool is of use to.

Currently we are focusing on Twitter and using Natural Language Processing to understand the sentiment of a tweet. However this is a very simple model of how language works. Language has content, context, conversation and meaning embedded in the words. To capture this and make our machine learning models as precise as possible, we will eventually include network analysis, computational linguistics and other techniques, so that we are as sure as we can be that the comment is misogynistic.

Also it is important to state here our commitement to understanding the biases and implications of the modeling that we are doing. We will also be looking into fairness metrics, dialect identification and model bias, to understand and communicate the limitations of our work.


## Where we are now

A high-level overview of how each of the tools are working.

### Browser Extension
We have curated a misogyny dataset and built have a binary classifier misogyny model which fuels the basic implementation of the browser extension. The browser extension is only available to use via github.

### Website
Our website is up and can be found at [optoutools.com](https://www.optoutools.com) but it is lacking content, design and GDPR help. Due to this, the report functionality is currently not working. If you can contribute any of these we'd be eternally grateful.

### Activism
We've held multiple workshops, not just around the topic of online misogyny. 

Our workshops include:

- Can we Measure the Inclusivity of Online Discussions?
- Consequence Scanning for Opt Out and Online Content Moderation
- Online Harassment: Let's talk.

If you'd like to know more about these, please each out at @OptOutSocial

### Research
We've done patchy but thorough research up until now. It's time to decide on a research roadmap. This roadmap is expected to include researching different definitions of misogyny at different levels, sociolinguistic study of misogyny and more.

### Modeling
We have a misogyny dataset and model, but we need to know how it's doing. We're currently in the process of writing error analysis scripts to do just that. We're also looking at more complex modeling deep learning architectures.

We shall also relabel two new datasets, one with a focus on labeling explicit misogyny and the other only labeling misogyny received by a specific group online.

## Our Short-Term Vision

### Browser Extension
The browser extension model needs to be improved. For that we need to know what it's labeling wrong. We are going to find a select number of users and release it to them with specific functionality, a Opt In and Opt Out buttons. These buttons will send the tweets to our servers and store the incorrectly labelled comments.

Alongside getting our minimum viable product gently out into the wild, we will work on fixing some bugs, modeling online misogyny and UX design.

### Website
Work will be mostly focusing on content, SEO and UX/UI design, trying to make our website as accessible, feminist and appealing as possible.

### Activism
Plan and action a kick-ass social media campaign!

### Research
- Portfolios of misogyny

### Modeling
- Network analysis
- Computational linguistics
- Multi - class labeling

## Our Long-Term Vision

### Browser Extension
- Automatic reporting
- local instance

### Website
- Virtual harassmap

### Activism
- Hacktivism
- Gamify activism

### Research

### Modeling
- Mix models



Redesign online spaces for a healthier online community.

## Tools Roadmap 

<p align="center"> <img src="opt_out_product_roadmap"> </p>


# The Repos and their Roles
An overview of the repositories we have an what they are there for

- [opt-out](https://github.com/opt-out-tools/opt-out): the front-end for the browser extension
- [website](https://github.com/opt-out-tools/website): the front-end for the website
- [public_ap](https://github.com/opt-out-tools/public_api): the joint back-end for the website and browser extension
- [theory-of-online-misogyny](https://github.com/opt-out-tools/theory-of-online-misogyny): qualitative research into online misogyny
- [study-online-misogyny](https://github.com/opt-out-tools/study-online-misogyny): quantitative research into online misogyny

# Use Our Tools
## Browser Extension

Our browser extension works only on Firefox. The code to load the browser extension can be found in [opt-out](https://github.com/opt-out-tools/opt-out).

To use the current version:
1. Clone a local copy of the master branch of the [extension repo](https://github.com/opt-out-tools/opt-out)
2. Start Mozilla Firefox (make sure you have the latest installed v69.0 at least)
3. Set the url to `about:debugging#/runtime/this-firefox` and hit enter
4. In the `Load Teporary Add-ons` box, open and load `manifest.json` which can be found in the `extensions` folder of this repo you cloned locally
5. Open Twitter and test!
6. If you make changes to the code you would like to test, make sure you click "reload" (left of the "remove" button) to apply new changes to script 

## Website
Go to our website [optoutools.com](https://www.optoutools.com) and click the submit a report button to submit details of your experience of online misogyny.

## Study Online Misogyny

## Activism 

## Research

# Develop Our Tools
## Architecture
<p align="center"> <img src="opt_out_architecture.png"> </p>


Above you can see a drawing of the architecture for both the browser extension and the website.

```
A key:
- square boxes are different repositories
- purple labels are the repository where the code for the component lives 
- blue is not implemented yet
- arrows indicate information exchange and flow
```
It is important to note that we do not currently have an automated model deployment mechanism.

The browser extension and website front-ends share a common back-end called public_api.

## Status of Repos

- [opt-out](https://github.com/opt-out-tools/opt-out): [![CircleCI](https://circleci.com/gh/opt-out-tools/opt-out.svg?style=svg)](https://circleci.com/gh/opt-out-tools/opt-out)
- [study-online-misogyny](https://github.com/opt-out-tools/study-online-misogyny): [![CircleCI](https://circleci.com/gh/opt-out-tools/study-online-misogyny.svg?style=svg)](https://circleci.com/gh/opt-out-tools/study-online-misogyny)


## [Browser Extension Front-end](https://github.com/opt-out-tools/opt-out) 
The browser extension removes online misogyny from an individual's Twitter feed. We have a binary classifier model sat on some servers and as the page loads the tweets are sent to the backend, the model is hit and returns a score. If the score indicates it’s misogynistic the text is blocked out, if not it’s left on the page. If there is an image attached to the comment that is also blocked. 

Tech stack:
- Javascript
- Tensorflow


## [Website Front-end](https://github.com/opt-out-tools/website)
This is the front-end for our website.
Tech stack:
- Javascript
- Angular 8.0


## [The Back-end](https://github.com/opt-out-tools/public_api)
This has two API's for the website and the browser extension.
Tech stack:
- Python
- Django

## [Modeling](https://github.com/opt-out-tools/study-online-misogyny)
We study online misogyny here. You can find our current work and our future plans here.

Tech stack:
- Python/R
- Data science (text analytics, network analysis.. etc.)

# Our Organisation

## Teams and Focus
The only thing better than being able to work on a project that really means something, is being able to work on it with a community of great people.

We have experts from across the world working with a variety of skills from UX to network analysis. More transparency to come.


# Code of Conduct
Please note that this project is released with a [Contributor Code of Conduct](https://github.com/malteserteresa/opt-out/blob/master/CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

## Disclaimer
Our intention is to **never ever** re-victimize anyone. However we deal with explicit content and sometimes we forget to sanitize a work or add a disclaimer that it may content explicit content. If this happens, please let us know and we'll rectify the matter immediately. 

# Help Our Vision

## Contributing
Opt Out is an open source project under active development. Currently, machine learning models are being evaluated for their ability to classify misogynistic text.  If you would like to contribute to the project, please see [Contributing](https://github.com/malteserteresa/opt-out/blob/master/contributing.md) first, and then check out the repos.

## Funding
If you would like to fund the project or make a donation, please email [Opt Out](mailto:opt-out-tool@gmail.com) or hit the sponsor button above, which will take you to our [Open Collective](https://opencollective.com/opt-out) page.


# Our Mission
We’re a mixed team , including social sciences, UX and lots of data nerds. We’re all working voluntarily in our spare time to make the internet accessible for all. What’s most important about us that we’re a group of people that **wont let hate win**.

We want to champion female-identifying people back into the online worlds they’ve been chased out of, support them and their voices whilst still protecting them and holding the perpetrators accountable. **We need to exist**.

If you share our vision, we ask you to **join us**. Whether it’s by talking about this to a friend, contributing, research, expertise, skills, strategy or code. Online misogyny is real and it's silencing the voices that society so desperately needs to hear.
  
<h3 align="center"> Let’s Opt Out</h3>

<p align="center"> <img src="built-with-love.png"> </p>

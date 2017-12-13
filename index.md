# Table of Contents

* The UH Essentials web application can be visited via this URL: [http://uhessentials.meteorapp.com/](http://uhessentials.meteorapp.com/)
* [About UH Essentials](#about-uh-essentials)
* [The Vision](#the-vision)
* [Developer Guide](#developer-guide)
  * [Installation](#installation)
* [Application Design](#application-design)
* [Development history](#development-history)
  * [Milestone 1: Mockup development](#milestone-1-mockup-development)
  * [Milestone 2: Application Functionality](#milestone-2-application-functionality)
* [Community Feedback](#community-feedback)
* [Contact us](#contact-us)

# About UH Essentials

Have you ever had a problem finding information about the UH Manoa Campus?

Well, with UH Essentials you can learn everything you need to know about ANY UH System campus, not just UH Manoa. UH Essentials is a forum-like Meteor application where you can learn about Degree Programs, Food Services, Commuting to, from, or around campus, Campus Security during the day and night, and Campus Events from actual students and professors that work or have experienced the UH life before.

When you come to the site, you are welcomed by the following landing page:

<img src="/images/M1-Landing-Page.png" width="800">

Anyone with a UH account can login to UH Essentials by clicking on the login button. The UH CAS authentication screen then appears and requests your UH account and password:

<img src="/images/Login.png" width="800">

Once authenticated, you can create a profile that allows you to provide personal information, including your standing, major, campus location, and so on:

<img src="/images/M1-Profile-Page.png" width="800">

Once your profile is created, you will be sent to the home page where you can explore the various threads available for viewing:

<img src="/images/M1-Home-Page.png" width="800">

After choosing a general topic you will be directed to the Top of the Topic page which shows all posts made in that specific Thread by other users of the system.

<img src="/images/M1-Thread-Page.png" width="800">

When clicking on an individual topic you will be directed to a page that looks likes this:

<img src="/images/M1-Topic-Page.png" width="800">

Below is the submission form if you would like to submit a question/information:

<img src="/images/M1-Submit-Page.png" width="800">

# The Vision

UH Essentials is a UH System wide dynamic Q&A Forum. Once a user logs in with his UH username and password, he can then proceed to creating a profile. To make the site more personal and specific to a user’s needs, the threads on the homepage will be based upon the information that he enters during the profile making process. There will be specific forums for each UH Campus of which you can only access once you create a profile. Each forum will look identical, but will hold different information about the campus from people who either work there or have attended that college campus before.  Each individual forum will hold a Home page that gives you 5 general topics to choose from to get more details or ask questions about: Degree Programs, Food Services, Commuting, Campus Security, and Campus Services. Some topics will have sub topics that you can explore more into detail--for example, Campus Services will have sub threads of Library Hours, Clubs, Events, Campus Jobs, etc. Once you have found the right thread that you want you can explore posts to your hearts content, up voting, down voting posts you like or even posting something new that hasn't been talked about yet. UH Essentials offers all the essential information you might want to know as a new comer or even a veteran who hasn't done much exploring around campus.

# Developer Guide

## Installation

To run UH Essentials, you will first need to [install Meteor](https://www.meteor.com/install).

Then, [download a copy of UH Essentials](https://github.com/uhessentials/uhessentials/archive/master.zip), or clone it using git.

Next, on command line, cd into the app/ directory and install libraries with:

```
$ meteor npm install
```

You may now run the UH Essentials app with:

```
$ meteor npm run start
```

Finally, the app can be seen at [http://localhost:3000](http://localhost:3000). In order to login and have further access to the app, you will need an account on the UH test CAS server, which uses valid UH credentials.

# Application Design

Coming soon...

# Development History

## Milestone 1: Mockup Development

This milestone started on November 4, 2017 and ended on November 22, 2017.

The goal of this milestone was to create mockups for our app, with the use of [Bowfolios](https://bowfolios.github.io/) as a template. During this milestone, we also practiced issue driven project management (IDPM) skills.

Mockup pages that were made include a landing page, home page, profile page, sample thread page, sample individual topic page, and a submit content page:

<img width="200px" src="/images/M1-Landing-Page.png"/>
<img width="200px" src="/images/M1-Profile-Page.png"/>
<img width="200px" src="/images/M1-Home-Page.png"/>
<img width="200px" src="/images/M1-Thread-Page.png"/>
<img width="200px" src="/images/M1-Topic-Page.png"/>
<img width="200px" src="/images/M1-Submit-Page.png"/>

Additionally, our application was deployed to Galaxy, and can be visited via this URL: [http://uhessentials.meteorapp.com/](http://uhessentials.meteorapp.com/)

This milestone was carried out through [UH Essentials Github Milestone M1](https://github.com/uhessentials/uhessentials/milestone/1):

<img src="/images/milestone-m1.png" width="800">

This milestone had eight issues, all of which our progress was tracked via [UH Essentials Github Project M1](https://github.com/uhessentials/uhessentials/projects/1). Each issue was implemented in its own branch, and was later merged back into master when the work for that issue was finished.

<img src="/images/project-M1.png" width="800">

## Milestone 2: Application Functionality

This milestone started on November 22, 2017 and ended on December 13, 2017.

The goal of this milestone is to implement the functionality features of our application. This includes:
- linking pages to each other
- working forms (ex. dropdowns, checkboxes, submission)
- creating a database for a profile collection and thread collection.

Although our ultimate goal is to have UH Essentials working and running for all UH campuses, as of right now, this application will only service the UH Manoa campus.

This milestone was be implemented through [UH Essentials Github Milestone M2](https://github.com/uhessentials/uhessentials/milestone/2).

The progress of the issues for this milestone were tracked via [UH Essentials Github Project M2](https://github.com/uhessentials/uhessentials/projects/2).

# Community Feedback

We asked five UH community members to test our application.

## Test User #1
### User Info
### Feedback

## Test User #2
### User Info
### Feedback

## Test User #3
### User Info
### Feedback

## Test User #4
### User Info
### Feedback

## Test User #5
### User Info
### Feedback

# Contact Us

Questions or Comments? Contact us at the following:

April Bala     
Email: aaibala@hawaii.edu

Creighton Gorai           
Email: cgorai@hawaii.edu

Kailey Pa'ahana         
Email: kpaahana@hawaii.edu

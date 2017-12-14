# Table of Contents

* The UH Essentials app can be accessed via this URL: [http://uhessentials.meteorapp.com/](http://uhessentials.meteorapp.com/)
* [About UH Essentials](#about-uh-essentials)
* [Developer Guide](#developer-guide)
  * [Installation](#installation)
* [Development history](#development-history)
  * [Milestone 1: Mockup development](#milestone-1-mockup-development)
  * [Milestone 2: Application Functionality](#milestone-2-application-functionality)
* [Community Feedback](#community-feedback)
* [The Vision](#the-vision)
* [Contact us](#contact-us)

# About UH Essentials

New to UH or want to learn more about your campus?

Well, with UH Essentials you can learn everything, you want to or need to know, about the campus that you are attending. UH Essentials is a forum-like Meteor application for the whole University of Hawaii (UH) system, where you can learn about Degree Programs, Food Services, Commuting to, from, or around campus, Campus Security during the day and night, and Campus Events from actual students and professors that work or have experienced the UH life before. The UH Essentials app offers all the essential information you might want to know as a new comer or even a veteran who hasn't done much exploring around campus.

When you first come to the site, you are welcomed by the following landing page. Which gives you an overview of what our site is about.

<img src="/images/landing-page.png" width="800">

Only those who are registered in the uh system by having a uh account may access this website. The UH CAS authentication screen then appears and requests your UH account and password:

<img src="/images/CAS-Login.png" width="800">

Once authenticated, you will be brought to the profile page where you will provide the following information: first and last name, your standing in your campus(Student, Professor, Faculty/Staff), a picture(optional), and bio(optional also).

<img src="/images/profile-page.png" width="800">

Once your profile is created, you can go to the home page where you can explore the various threads available and even take a peek at recently asked questions users have submitted in a dropdown. From this page you will be able to click the the title of a thread genre which brings you to questions which were posted in that specific thread genre or click a specific thread topic in the dropdown which will bring you to the specific topic page.

<img src="/images/home-page.png" width="800">

This is how it looks on a specific thread genre page. You will be able to submit a new topic by clicking the big green button on the top or scroll through posts already made. Topics recently submitted will be on the top of the front page.

<img src="/images/thread-page.png" width="800">

When clicking on an individual topic you will be directed to a page that looks likes the picture you see below. On the top of the page you will see the question/information the user has given, users name, and the time of which they posted. Below that you will be able to vote on the post based on how useful or not useful this was to you. Then the bulk of this page will be filled up by comments that you are able view and give.

<img src="/images/topic-page.png" width="800">

The last image you see below is the submit page. As you can see on the top of the page there will be a set of rules that you are to abide by. If any rules are broken the post will be deleted by the admin who run the site. You will also see a checkbox of which you have to check to agree by the rules you have seen above. If the box isn't checked admin will delete the post you have made. After that you enter in your standard information: title, thread(which thread you would like the post to), and give extra information(if needed).

<img src="/images/submit-page.png" width="800">

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

# Development History

## Milestone 1: Mockup Development

This milestone started on November 4, 2017 and ended on November 22, 2017.

The goal of this milestone was to create mockups for our app, with the use of [Bowfolios](https://bowfolios.github.io/) as a template. During this milestone, we also practiced issue driven project management (IDPM) skills which we learned from ICS 314 at UH Manoa.

Mockup pages that were made include a landing page, home page, profile page, sample thread page, sample individual topic page, and a submit content page:

<img width="200px" src="/images/M1-Landing-Page.png"/>
<img width="200px" src="/images/M1-Profile-Page.png"/>
<img width="200px" src="/images/M1-Home-Page.png"/>
<img width="200px" src="/images/M1-Thread-Page.png"/>
<img width="200px" src="/images/M1-Topic-Page.png"/>
<img width="200px" src="/images/M1-Submit-Page.png"/>

Additionally, our application was deployed to Galaxy, and can be visited via this URL: [http://uhessentials.meteorapp.com/](http://uhessentials.meteorapp.com/) (There is also a link to this site on the top of this documentation)

This milestone was carried out through [UH Essentials Github Milestone M1](https://github.com/uhessentials/uhessentials/milestone/1):

<img src="/images/milestone-m1.png" width="800">

This milestone had eight issues, all of which our progress was tracked via [UH Essentials Github Project M1](https://github.com/uhessentials/uhessentials/projects/1). Each issue was implemented in its own branch, and was later merged back into master when the work for that issue was finished.

<img src="/images/project-M1.png" width="800">

## Milestone 2: Application Functionality

This milestone started on November 22, 2017 and ended on December 13, 2017.

The goal of this milestone was to implement significant functionality features to our application. This includes:
- linking pages to each other
- working forms (ex. dropdowns, checkboxes, submission)
- creating a database collections for campus, thread, and topic.

Although our ultimate goal is to have UH Essentials working and running for all UH campuses, as of right now, this application will only service the UH Manoa campus.(You may view our whole vision for this project below in the section titled "The Future Vision")

This milestone was be implemented through [UH Essentials Github Milestone M2](https://github.com/uhessentials/uhessentials/milestone/2).

The progress of the issues for this milestone were tracked via [UH Essentials Github Project M2](https://github.com/uhessentials/uhessentials/projects/2).

# Community Feedback

We asked five UH community members to test our application.

## Test User #1
### User Info
Mary Pascual, Attends: UH Manoa, Major: Computer Science
### Feedback
When I first go to the website, visually, the color is appealing.  However, I don’t understand why there’s pictures of the websites.  I think it would’ve looked better to use pictures from google showing actions of the latest topic or to at least show a thread on the website of the latest topic.  Also, I almost missed the login button because of how small it is compared to everything else on the page.  The landing page is neat because everything is put into categories, which makes the search easier.  However, I do think that too many topics show up (which I don’t like in Reddit either which I know it was the website this project was based on).  I think having two to three topics and then a link to go to the category page, which would show all the questions for that topic would’ve been better.  Lastly, in the actual thread page, it’s very appealing and I like that people can comment their answers.  I think they should also include a like and dislike button for the comments because comments can get overpopulated or someone might put the wrong answer.  With the like/dislike button, students will know which answers are the correct answers and which are wrong.

### Test User #2
#### User Info
Sawinna Huang, Attends: UH Manoa, Major: Electrical Engineering
#### Feedback
First of all, I don’t like how you have to put in your name because I don’t want people to know who I am. So is there a option for anonymous? Secondly, can UH staff faculty answer those questions too? If you made it more creative and added more design or their UH logo etc, it’s something that will catch their attention more. Like I would love to look at sites that are pretty or creative looking because they grab my attention. And try to use a better picture for the home page as well- don’t put a screenshot because people don’t need that, just put a sentence of what the picture is about if you need to instead of a screenshot because it looks out of place or just like you didn’t put much effort in it

### Test User #3
#### User Info
#### Feedback

### Test User #4
#### User Info
#### Feedback

### Test User #5
#### User Info
Joey Iida, Attends: UH Manoa, Major: Biology
#### Feedback
The concept seems useful, but the site doesn't function properly. If the concepts can be put into play I think this will be a useful site.

# The Future Vision

Our vision for this project is to use UH Essentials for ALL UH campuses. When first logging in you will be greeted by a profile page which you will be required to enter in specific information one of the options being, which UH campus you are attending. You will be able to choose multiple if you are also affiliated with the other campuses. You will be able to change this through your profile. Once the profile page is finished and you submit you will be brought to the Home page where you can start your adventure by looking at various posts people have made. 
We also wanted to implement a sorting section on each individual thread page to sort by topics that have the most votes over all, most votes in a certian period of time, or even give a wiki page which gives links to various uh websites for more information about their campus.
The smaller things we want to implement later are giving more information on a single topic that you can see from a thread page. This will include things like the posters standing and the number of comments submitted to that post.
Unfortunately, we were not able to expand our application for other UH system campuses to use. As of right now, the UH Essentials app is geared only for the UH Manoa campus. In the future, we hope to expand our application more by allowing all UH campuses to have their own personalized thread pages fitted for the u

# Contact Us

Questions or Comments about this projectf? Contact us at the following:

April Bala     
Email: aaibala@hawaii.edu

Creighton Gorai           
Email: cgorai@hawaii.edu

Kailey Pa'ahana         
Email: kpaahana@hawaii.edu

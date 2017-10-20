---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-10-19
labels:
  - Software Engineering
  - Meteor
---

# Meteor Development

Meteor is a JavaScript framework which helps developers to design and code apps much easier and safe time. Meteor can provide sample templates to work off on and supplies users with a lot of libraries functions that they may call for functionality inside their application. This is in contrast to the android development experience that I have had so far as when developing in android, most of the applications I have written have been built from the ground up. Meteor makes it much easier to develop web applications and gives developers a better overall experience. One thing that is made easier in Meteor is the installation of packages that offer many features for the developer. These packages are easily installed via a command line command such as 'meteor install PACKAGE'. Not only do these packages offer advanced libraries, but they also give users some enhacements for user interface, therefore enhancing the user experience as well.

# Meteor's Most Tedious Problem

One problem that I have been encountering the most in Meteor is the failure on my part to link some of the JavaScript and HTML files to the higher modules. Not linking the files in the index.html file leads to many problems and the web application will not know where to look for the certain functions or references you are making. One example of this is clearly illustrated when I tried to make a new page in my digits app. The new page "home-page" was supposed to let users see the contact list of people that have been added to the database. In the beginning none of the names were showing up due to me not linking the correct paths. If there is one thing beginning Meteor developers need to keep in mind, it is to always link the source files because it will cut down on debugging and confusion.

# A Meteor Problem I had the Most Trouble With

While developing the second stage of the digits app I encounterd a problem that I struggled with, alothough it was a simple and easy fix. For the assignment I had to create a new page that allowed users to add new contacts into the list. I had followed all of the instructions correctly but my home page on the web interface did not display what I had wanted. I had not watched the tutorial video carefully enough and I thought the home page of the application was supposed to change. What I did not know until later was that to get to the new page I had to enter the page in the url after a slash so for example it would be 'myurl/add-contact'. I also noted that there was no link to the page and this observation led to my eventual discovery of the solution. Hopefully anybody reading this will be able to avoid the simple mistake/misunderstanding that I had.

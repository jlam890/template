---
layout: project
type: project
image: images/micromouse.jpg
title: HIDRA
permalink: projects/HIDRA
date: 2017
labels:
  - Android Studio
  - Java
  - SQL
  - Raspberry Pi
  - Mapbox
summary: My team developed a proof of concept android application with the goal of supplementing first responders in a disaster scenario.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>

For the summer I was a part of an intern team for Booz Allen Hamilton. We were tasked with creating a proof of concept to help secure more funding for a HADR (Humanitarian Assistance and Disaster Relief) tool. We came up with HIDRA or the Humanitarian Interconnected Disaster Relief Assistant. HIDRA is able to detect other wireless technologies like bluetooth, nfc, and rfid and plot the data onto a map for display. Imagine a scenario where a first responder is walking through the aftermath of a disaster. With HIDRA they could see some bluetooth signals which could be signs of victims in need of help. New resources can be scanned in via RFID tags or NFC chips and indicate where the food, water, and other supplies are located.

For this project I was one of three software developers working on the android application. I was responsible for implementing a bluetooth low energy service that would run in the background of the app periodically scanning for new bluetooth devices. Once I finished this service I moved on to developing the interface for RFID scans. I also designed the simple local SQL database for HIDRA. We also had a server running on a raspberry pi that would accept HTML requests from our mobile app. Another team member implemented the actual HTML request and I was tasked with integrating into our project so that the server could understand our input. As a test we walked around downtown Honolulu during one lunch break with our phones and were able to plot the collected signals onto our MapBox generated map. We also tested it in a ballroom during our final week of the internship in Washington DC, and from the about 400 people we were able to pick up 75 unique device signals from a fixed location. 

This was my first big software development project and I learned many valuable skills. These include proficiency in GitHub, time management using agile methodology, and introduction to other software languages. 










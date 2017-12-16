---
layout: project
type: project
image: images/activityfinderlogo.png
title: Activity Finder
permalink: projects/activityFinder
date: 2017
labels:
  - JavaScript
  - HTML/CSS
  - Meteor
  - MongoDB
summary: Web application build using the Meteor framework for UH Manoa community members to schedule activities and events. UH members can create events, join/leave events, and see who else is going to the events.
---

<img class="ui image" src="{{ site.baseurl }}/images/activityfinderlogo.png">

Going to website first takes you to our landing page. Below is a screenshot of our landing page.

<img class="ui image" src="../images/activityfinderlandingpage.png">

Only users with a valid UH login can access the website. Once done logging in users are taken to event calendar page. The event calendar page displays all events available in the database. Red events are ones that the current user has already joined and blue events are ones that are still open to join. There is also a filter feature where users can filter out interests so that they can narrow down events to find the ones they want to join. Clicking on an event will then take users to the event list page where all the events are displayed containing more information. Here additional information like the location, people going, and a description is shown. Clicking on the leave/join button will perform the specified action and also users can delete their created events by clicking the delete button. Lastly the Create Event page is where users can create a new event and insert it into the database.

The project was completed by a team of three software developers. My task for the project was working on the backend development. I was in charge of creating the MongoDB schema for the events and making sure all the database operations worked correctly. I was able to use JavaScript to define the actions that happened once a ui button as clicked. Specifically I polled the MongoDB collection for information on event goers to determine the people going, inserted newly created events into the collection, and updated collections when new users requested to join. Lastly, I worked with spacebars to help determine which ui buttons would show up depending on the state of the collection.

Activity Finder was my first web application that I helped design and overall it was an amazing experience. Having only previous experience in mobile app developement my dive into the web application developement was quite refreshing. During the development of the project we used GitHub issues to keep track of tasks and communicated through Slack messaging. I was able to further hone my JavaScript, HTML/CSS, and ui design skills through the development of this project.

For more information here is the <a href="https://activityfinder.github.io">Project Website</a>

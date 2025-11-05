---
layout: essay
type: essay
title: "Final Project Idea"
# All dates must be YYYY-MM-DD format!
date: 2025-11-04
published: True
labels:
  - Software Engineering
  - Nextjs
---

## UH Manoa Event Organizer
#### Proposers: Jazz Lam, Caleb Zerbe
<br/>

## Overview
#### The Problem:

Throughout the semester, many students do not know what events are going on until the event is already happening or when it is already too late. There is a page that lists all current events that is hosted by UH, however it is simply designed as a list, overcrowding and overwhelming students as they look through the events posted. The information is not sorted by anything other than by campus. There are also no ways of viewing past events to know what to expect for the future.

#### The Solution:

UH Manoa Event Organizer would be a digital platform for uploading and locating events on the UH Manoa campus. Users can upload and/or update information on events that will be occurring, which will then be posted to a main page which will display all current events happening on campus with a map showing the location of each event and further information once a user clicks on the event. Users can look for specific events occurring on a given date/semester, as well as look at past events, and will be able to set reminders via SMS or email, which will inform them prior to the event occurring. 
<br/>

## Approach

For this app, we will create a campus-wide way to create, update, and locate events on the UH Manoa campus. There are three roles: Users (students), Faculty & Staff, and Admin (designated staff). Any user will be able to view events, view campus location of events, search for tags, favorite/set reminders for events. View a separate listing of past campus events sorted by semester. Authorized staff and faculty will be able to create listings for their events that will be able to be sorted and listed. Set location, time, semester, campus, searchable tags, description, an automatically scaled image. They will also be able to edit and delete events. They will also be able to add students as approved editors. Students will be able to create the same listings but it would have to go through approval of their faculty sponsor. Students will be able to request deletion/cancellation of their events.

The UH Manoa Event Organizer app will provide an easily accessible database of reported campus events. In addition to listing things by campus location, tags, favorite events, and semester of the event, users can filter events by keywords, date and time of the event, and event sponsor.
<br/>

## Mockup Concepts

#### Landing page (Normal User)
Feed
* Shows upcoming events and calendar.

Dashboard
* Home, search, all events, login.

Map
* Map displaying the UH Manoa campus with markers of the locations of ongoing events for the month.
<br/>

#### Landing page (Student)
Feed
* Shows my events, lists upcoming events, and shows recommended events (listing events with favorited tags, calendar).

Dashboard
* Home, search, all events, my events, and the option to create/edit an event.

Map
* Map displaying the UH Manoa campus with markers of the locations of ongoing events for the month.
<br/>

#### Landing page (Faculty & Staff)
Feed
* Shows my events, lists upcoming events, and shows recommended events (listing events with favorited tags, calendar).

Dashboard
* Home, search, all events, my events, and the option to create/edit an event.

Map
* Map displaying the UH Manoa campus with markers of the locations of ongoing events for the month.
<br/>

#### Authentication Page
Login
* Prompts user to log in using UH username and password.
<br/>

#### Faculty & Staff Page
Create/Edit Event
* User will redirected to a form with the ability to upload/edit event location, time, semester, campus, searchable tags, description, add an image, and add students via username to a list of those who can edit your event.
<br/>

Event Approval
* User will be able to see all events which requested them as a sponsor, and approve or deny the event’s addition to the events listing.
<br/>

#### Student Event Creation Page
Create/Edit Event
* User will redirected to a form with the ability to upload/edit event location, time, semester, campus, searchable tags, description, add an image, user will have to input a authorized faculty username.

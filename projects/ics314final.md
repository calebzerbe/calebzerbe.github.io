---
layout: project
type: project
image: img/ImageForProfessionalPortfolioStudyBuddy.jpg
title: "Study Buddy - ICS 314 Final Project"
date: 2025-12-12
published: true
labels:
  - HTML
  - CSS
  - JavaScript
  - TypeScript
  - React
  - Bootstrap
  - PostgreSQL
  - Prisma
  - Nextjs
  - Vercel
summary: "My team and I created a study application that allows University of Hawaii students to connect online and form study sessions for ICS courses."
---

## Overview

The main goal of creating the Study Buddy application is to create a space where University of Hawaii students can connect with each other and form study commmunities, to help students build a stronger knowledgebase and improve the acquisition of knowledge on UH campuses through shared cooperation. In particular, this app was specifically built for ICS users to connect and form study sessions to aid in their progress throughout the semester. 

In order to achieve this goal, the app was built to allow users to create study sessions which other users can attend. Each session is dedicated to one ICS course, and lasts no more than a day. Users can view their own sessions that they've created in a listed format as well as on the calendar. Users can also view all sessions, which can be filtered down by class, location, owner, and more. These sessions, like the personal user sessions, can be viewed on the calendar for all University of Hawaii students to see. To make things a little more interesting, users are also ranked by the number of sessions that they've created, so you can see how you compare to others in terms of participation within the application.

## Project Reflection

For this experience, I was primarily responsible for anything related to the database. This meant creating the entity-relationship model within the prisma schema and seeding the database (the only thing seeded were the available user courses, otherwise everything else was created by test users and other UH Manoa students), in addition to doing anything related to database calls. Because of this, I worked a lot with the user profile, updating the sign up page to allow users to create a user name and select the courses they are enrolled in, give the ability for users to add a description and profile image, as well as create an edit profile page to allow users to change their information as they please (except their email, as well as their password, which can be changed on another page). I also worked a lot on the create session pages, creating a skeleton form that allowed the user to select a time for their session, select the course that it is for, provide a location, and any extra details in a description, then connecting that to the database and registering it to a user. In addition to the create session page, I worked on the edit session page, which is basically the same as the create session page, and also gave users the ability to delete their sessions. Along with everything else, I was the primary host for the website, utilizing Vercel to host the site.

Working on this project taught me a lot of things. First was how design patterns tie into the process of developing software. The most visible design patterns throughout the project were FrontController and Model-View-Controller, to name a few. I also learned how to work utilizing Agile Project Management, which in this course was done through Issue-Driven Project Management, a form of Agile Project Management that relies on using GitHub issues to manage members' tasks which allows the team to constantly see the progress of the project and quickly identify room for improvement and things to modify. Each set of issues were separated into multiple milestones, in this case three milestones, which each catered towards a different part of the project. This was all done in combination with effort estimation, to give us a better idea of how long each task would take and to help us plan accordingly. In addition to design patterns and project management, I became well acquainted with many tools involved in full-stack development, which for this project included but was not limited to: HTML, CSS, Typescript, Prisma, PostgreSQL, and Nextjs, among others. The full technology stack will be displayed below. Last but not least, I learned how to coordinate with a team to approach a problem, assign tasks, and create a fully-functioning deliverable on a deadline.

#### Technology Stack

- Language: HTML, CSS, TypeScript, and JavaScript
- Styling: React-Bootstrap
- Framework: Next.js (React framework with server-side rendering)
- Database: PostgreSQL with Prisma ORM
- Authentication: Google OAuth (UH email required)
- Integrations: Javascript Full Calendar
- Hosting Platform: Vercel
- Code Quality: ESLint and Prettier
- Testing: Playwright for end-to-end testing
- Version Control: Git and GitHub with Issue-Driven Project Management

## Website View

Below I will provide some example images of the sign up page, user profile page, create session page, user calendar page (not the main calendar that all users can see), and the all sessions page so you can take a look at our work.

<div class="text-center p-4">
  <img width="700px" src="../img/projectimages/Study Buddy Sign Up Page.png" class="img-thumbnail" >
  <p style="text-align: center;">Sign Up Page</p>
</div>

<div class="text-center p-4">
  <img width="700px" src="../img/projectimages/Study Buddy User Profile Page.png" class="img-thumbnail" >
  <p style="text-align: center;">User Profile Page</p>
</div>

<div class="text-center p-4">
  <img width="700px" src="../img/projectimages/Study Buddy Create Session Page.png" class="img-thumbnail" >
  <p style="text-align: center;">Create Session Page</p>
</div>

<div class="text-center p-4">
  <img width="700px" src="../img/projectimages/Study Buddy My Calendar Page.png" class="img-thumbnail" >
  <p style="text-align: center;">User Calendar Page</p>
</div>

<div class="text-center p-4">
  <img width="700px" src="../img/projectimages/Study Buddy All Sessions Page.png" class="img-thumbnail" >
  <p style="text-align: center;">All Sessions Page</p>
</div>

## Project Information

If you would like to visit the project to learn more about it, you can visit our github page <a href="https://study-buddy-g2s6.github.io/">here</a>.

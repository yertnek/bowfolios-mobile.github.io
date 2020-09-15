# Table of Contents
* [Overview](#overview)
* [Project Links](#links)
* [Project Milestones](#milestones)
* [User Guide](#guide)
* [Developer Guide](#devguide)
* [Team Members](#members)

<a name="overview"></a>
# Overview
BowFolios Mobile is an mobile app of the original BowFolios web application. Users have the ability to create a profile, add interests, and profiles. It provides the ability to view and modify profiles, projects, and interests. It is a quick way to find other UH Manoa students with the same interests and view their previous and current projects. 

For Milestone 1, we created the user interface for the login, create account, profiles, interests, projects, drawer navigation, and set up firebase for backend data storage and user authentication. Users can currently login, but not logout.

For Milestone 2, we plan to implement backend features to the profiles, interests, projects page, and implement a logout feature. We also want to route the widgets in the drawer navigation.

<a name="links"></a>
### Project Links
* [GitHub Project Board](https://github.com/yertnek/bowfolios/milestones)
* [GitHub Source Code](https://github.com/yertnek/bowfolios)

<a name="milestones"></a>
# Project Milestones
### [Milestone 1](https://github.com/yertnek/bowfolios/milestone/1)
The purpose of Milestone 1 is to have a partially working version of BowFolios.

### Milestone 2 (In Progress)
The purpose of Milestone 2 is to improve upon features made in Milestone 1. Main goal is to implement backend functionality in current pages and a logout feature.

<a name="guide"></a>
# User Guide

### Profiles Page
The profiles page is presented to users when they first open the app. The profile page shows a list of users and the projects 
and interests associated with each specific user.
<img src='./doc/profile_mockup.png'>

### Projects Page
The projects page shows a list of the projects and the users and interests associated with each specific project.
<img src='./doc/projects_mockup.png'>

### Interests Page
The interests page shows a list of the interests.
<img src='./doc/interests_mockup.png'>

### Drawer Navigation
The drawer navigation is used to redirect back home, the users profile page, the add project page, and the search page.
<img src='./doc/nav_mockup.png'>

<a name="devguide"></a>
# Developer Guide
This section provides information on how to get the application to run on a developers local machine.

### Installation
First, follow the steps [here](https://flutter.dev/docs/get-started/install) to get flutter set up.

Once flutter is installed, clone the [repo](https://github.com/yertnek/bowfolios).

Next change directories into the projects folder.

Make sure you have a virtual device running, and start the application by running the following command:
```
$flutter run
```
The application will take a little while to start up, but once it does you should land on a login page and you are all set to use the app!

<a name="members"></a>
# Team Members
* [Trey Sumida](https://github.com/trey-sumida)
* [Ken Tung](https://github.com/ken-10)






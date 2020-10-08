# TugetherApp

## Description - Eva Veskova

The goal of this project is to connect people who want to find a coding partner to build projects.

## Objectives - Eva Veskova

# General Objectives

# Specific Objectives

## Requirements - David Auza

### Functional Requirements

1. System must allow users to sign up for the application.

2. System must allow users to sign in for the application.

3. System must allow searching for other users and connecting with them.

### Non-Fuctional Requirements

1. User experience must be friendly and simple.

2. System must be available 95% of the time.

## Use Cases - David Auza

## Use Case Diagram - David Auza


## User Stories - Aaron Newbold

As a user I want to be able to:
1. Sign up to the service so that I get access to other user's profiles.
2. Add the technologies I'm learning so that I can match with other users using the same 
technology.
3. Search for other users based on specific technologies so that I can invite them to my network.
4. Create new Posts to show off Projects.
5. Comment on Posts.
6. Recieve notifications when someone comments on my Post or wants to link up.
7. Send an instant message to a potential partner.

## Team Description - Aaron Newbold

### Front-end Team
Handles the building of User Interfaces(UI) with a more direct influence to the User Experience (UX). This includes the webpages that the users will see and interact with in order to:

1. Register/Sign-up
2. Log-in
3. Search for Technologies to Learn
4. Search for other Users to collaborate with.
5. Contact other Users.
6. Links to Backend API which handles database.  
...


### Back-end Team
Handles the building of the Backend Application Program Interface (API) which provides the Front-end access to a database. Requests are made by the Front-end to GET, POST or UPDATE data which will then be handled and processed by the Back-end resulting in either the return or saving of data. The Back-end team will need to create: 

1. Database models (Users, Technologies, ConnectedUsers, Notifications, Posts, Comments, InstantMessaging)  
  a. Model Associations. eg Post has many comments, Post has one author(User).
2. Model Tests and Controller Tests.
3. Controllers for all models.  
  a. User(or Sessions) Controller (Handles registration and logins)  
  b. ConnectedUsers Controller (Handles User friending/connections)  
  c. Technologies Controller (Handles Technology listing and search criterias)  
  d. Notifications Controller...  
  e. Posts Controller (Handles creation(POSTing), updating, deletion of posts)  
  f. Comments Controller (Handles creation, updating and deletion of comments)  
  g. InstantMessaging Controller (Handles messaging between users)
4. Routes for all controllers and request methods.  
...

## Entity Definition - Hugo Passos

1. User: The individual using the application. 

2. Friend: A user other than me, using the application, with whom I have connected.

3. Technologies: The different technologies a user adds to its profile.

4. Timezone: The timezone a user lives in.

## Entity Relation Diagram - ERD - Hugo Passos

## User Interface Proposal - Adebola Adeniran

## Navigation Diagram - Andrés Rodríguez





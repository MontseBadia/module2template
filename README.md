# Project Name

## Description

Describe your project in one/two lines.
 
 ## User Stories

List of user stories in order of priority/importance.

Example:
 - **404** - As a user I want to see a nice 404 page when I go to a page that doesn’t exist so that I know it was my fault 
 - **500** - As a user I want to see a nice error page when the super team screws it up so that I know that is not my fault
 - **homepage** - As a user I want to be able to access the homepage so that I see what the app is about and login and signup
 - **sign up** - As a user I want to sign up on the webpage so that I can see all the events that I could attend
 - **login** - As a user I want to be able to log in on the webpage so that I can get back to my account
 - **logout** - As a user I want to be able to log out from the webpage so that I can make sure no one will access my account
 - **events create** - As a user I want to create an event so that I can invite others to attend
 - **events list** - As a user I want to see all the events available so that I can choose which ones I want to attend
 - **events detail** - As a user I want to see more information regarding one event so that I can decide if I want to attend 
 - **event attend** - As a user I want to be able to attend to event so that the organizers can count me in

## Backlog

List of other features outside of the MVPs scope

User profile:
- see my profile
- upload my profile picture
- see other users profile
- list of events created by the user
- list events the user is attending

Event Location
- add geolocation to events when creating
- show event in a map in event detail page
- show all events in a map in the event list page

Homepage
- ...


## ROUTES:
```
GET / 

GET /auth/signup
POST auth/signup - POST Body: username, password
GET /auth/login
POST /auth/login - POST Body: username, password
POST auth/logout - POST Body: nothing

GET /events
POST /events/create - POST Body: name, date, location, description
GET /events/:id
POST /events/:id/attend - POST Body: nothing (the user is already stored in the session)

```

## MODELS

```
Event
 - name: String
 - description: String
 - date: Date
 - location: String
 - attendees: ObjectId
```    
 
```
User
 - username: String
 - password: String
```

## Links

### Trello

[Link to your trello board](https://trello.com)

### Git

The url to your repository and to your deployed project

[Repository Link](http://github.com)

[Deploy Link](http://heroku.com)

### Slides.com

The url to your presentation slides

[Slides Link](http://slides.com)





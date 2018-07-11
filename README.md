# Project Name

## Description

Describe your project in one/two lines.

Example:
 - 404
 - 500
 - homepage
 - sign up
 - login
 
 ## User Stories

List of user stories in order of priority/importance.

Example:
 - 404 - As a user I want to see a nice 404 page when I go to a page that doesn’t exist so that I know it was my fault 
 - 500 - As a user I want to see a nice error page when the super team screws it up so that I know that is not my fault
 - homepage - As a user I want to be able to access the homepage so that I see what the app is about and login and signup
 - sign up - As a user I want to sign up on the webpage so that I can see all the events that I could attend
 - login - As a user I want to be able to log in on the webpage so that I can get back to my account
 - logout - As a user I want to be able to log out from the webpage so that I can make sure no one will access my account
 - events list - As a user I want to see all the events available so that I can choose which ones I want to attend
 - events detail - As a user I want to see more information regarding one event so that I can decide if I want to attend it 
 - event attend - As a user I want to be able to attend to event so that the organizers can count me in

## Backlog

List of the user stories outside of the MVPs scope in order of priority/importance

Example:
 - user profile
 - list of events per user
 - share an event
 - event listed in maps
 - event picture


## ROUTES:
````
GET / 
GET /auth/signup
POST auth/signup - POST Body: username, password
GET /auth/login
POST /auth/login - POST Body: username, password
POST auth/logout - POST Body: nothing

GET /events
GET /events/:id
POST /events/:id - POST Body: nothing (the user is already stored in the session)
GET /profile
POST /profile

````

## MODELS
````
events
 - name: type String
 - date: type Date
 - location: type String
 - attendees: type ObjectId

 ````    
 
````
users 
 - username: type String
 - password: type String
````

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





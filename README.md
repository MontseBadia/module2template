# Project Name

## Description

Describe your project in one/two lines.

## MVP

Definition of the MVP with a list of user stories in order of priority/importance.

Example:
 - 404
 - 500
 - homepage
 - sign up
 - login
 
 ## User Stories

Definicion de las tareas por orden de prioridad

## Backlog

List of the user stories outside of the MVPs scope in order of priority/importance

## ROUTES:
````
/ - The homepage
GET /auth/login
POST /auth/login
GET /auth/signup
POST auth/login

GET /movies
GET /movies/:id
POST /movies/:id
GET /profile => GET
POST /profile/:id 

````

## MODELS
````
movies {
  name: {
    type: String,
    required: true
  },
  type: {
    type: Number,
    required: true
  },
    year: {
      type: Number,
      required: true
     },
      celebrities: [{
       type: ObjectId,
       required: true
      }]
      }
  ````    
````
celebrities {
  name: {
    type: String,
    required: true
  },
  age: {
    type: Number,
     required: false
  }
}
````

````
users {
  name: {
    type: String,
    required: true
  },
  email: {
    type: String,
     required: true
},      
  password: {
    type: String,
    required: true
  },
  role: String(enum 'admin', 'user')
}
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

[Link Slides.com](http://slides.com)





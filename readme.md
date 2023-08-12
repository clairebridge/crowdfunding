# Moovment
by Claire \
She Codes crowdfunding project - DRF Backend.

## About
This website is called Moovment - a corwdfunding website targeted at those who want to help reduce animal creulty and find creatures loving homes.

## Features
* [X] Create new users
* [X] Log in and log out
* [X] Create a new project (as a owner)
* [X] Pledge to one or many projects (as a supporter)
* [X] View details about a project



### Stretch Goals
{{ Outline three features that will be your stretch goals if you finish your MVP }}

* [  ] View my profile details and pledges I have made and projects I own


## API Specification



## Database Schema
{{ Insert your database schema }}

![image info goes here](./docs/image.png)

## Wireframes
{{ Insert your wireframes }}

![image info goes here](./docs/image.png)

## Colour Scheme
![image info goes here](./docs/image.png)

## Fonts
{{ outline your heading & body font(s) }}

## Submission Documentation
{{ Fill this section out for submission }}

Deployed Project: [Deployed website](http://linkhere.com/)

### How To Run
{{ What steps to take to run this code }}

### Updated Database Schema

![image info goes here](crowdfunding/img/schema.png)

### Updated Wireframes


![image info goes here](crowdfunding/img/wireframes.png)

### How To Register a New User
* set to "post" request
* use the address "http://localhost:8000/users/"
* In the JSON, input data for the new user (e.g - 
{
	"username":"Test",
	"password":"Test",
	"email":"test@gmail.com"
})
* Send request, expected output should be a "200 OK" success message, and preview of new user details.
![image info goes here](crowdfunding/img/new_user.png)


### Screenshots
* A screenshot of Insomnia, demonstrating a successful GET method for any endpoint.
![image info goes here](crowdfunding/img/GETrequest.png)

* A screenshot of Insomnia, demonstrating a successful POST method for any endpoint.
![image info goes here](crowdfunding/img/POSTrequest.png)

* A screenshot of Insomnia, demonstrating a token being returned.
![image info goes here](crowdfunding/img/Usertoken.png)
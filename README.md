# NoSQL:Social Network API

## Table of Contents
- [Description](#description)
- [What to expect](#what-to-expect)
- [Tools and Languages](#tools-and-languages)
- [GitHub](#github)
- [Installation](#installation)
- [Usage](#usage)
- [Walkthrough Video](#walkthrough-video)


## Description
This project is an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list, using Express.js for routing, a MongoDB database, and the Mongoose ODM.

## What to expect
* When user enter the command to invoke the application, the server is started and the Mongoose models are synced to the MongoDB database.
* On opening API GET routes in Insomnia for users and thoughts, the data for each of these routes is displayed in a JSON format.
* Testing API POST, PUT, and DELETE routes in Insomnia, user is able to successfully create, update, and delete users and thoughts in the database.
* Testing API POST and DELETE routes in Insomnia, then user is able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list.

## Tools and Languages
* MongoDB 
* Mongoose
* Express
* Node
* Nodemon

## GitHub
* GitHub: https://github.com/sinka27/NoSQL-Social_Network_API

## Installation
 * Clone this repo to your machine
 * Open up the terminal and run "npm install". This will install the necessary packages and dependancies needed to run this API.
 * Application is ready to be used. Refer to the Usage section for futher instructions.
 
 ## Usage
 * To start the application once everything is installed you can run nodemon server.js to start the process and create your network
 * Open insomnia and create routes for each table and their purpose(delete, update, get)
 * Run the routes with the correct host to use the database.
 
 ## Walkthrough Video
 You can view a walkthrough video of the app [here]()
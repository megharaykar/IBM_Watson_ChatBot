# IBM_Watson_ChatBot
A customer service chatbot using IBM Watson Conversation API

Introduction

Digital assistant for customer support provides a single platform for customers to easily connect with organizations. It sends immediate responses to address any issue that a customer has. The digital assistant is trained to respond to the key issues using IBM Watson. It is trained to raise tickets for every new issue that Watson doesn’t recognize. Also, the digital assistant can monitor the issues and prioritize issues based on number of issues in a category. This helps organization to keep track of issues based on categories.

Requirements

Node
Express
Neo4j - https://www.graphenedb.com/
Credentials Setup

Neo4j- Get the cloud url generated by following the above link and also get username and password.
IBM Watson Conversation Api- Get the username, password and workspace id by logging in into IBM conversation api https://www.ibmwatsonconversation.com/login
Getting started

To get the Node server running locally:

Clone this repo
npm install to install all required dependencies
npm install
npm start to start the local server
npm start  
Code Overview

Dependencies

expressjs - The server for handling and routing HTTP requests
nodemailer- For sending emails through gmail account
neo4j- The NoSQL graph database to store the tickets or issues
IBM Watson Conversation Api- For Digital assistance and sending response to the users
Application Structure

./bin/www- This is where the server is started
app.js - The entry point to our application. This file defines our express server. It also requires the routes we'll be using in the application.
./routes/index.js - This is where we have defined express routes to different screens and it also contains the logic for communicating with IBM watson Conversation API. Please provide the credentials for IBM watson Conversation API, Neo4j Database and Gmail Account.
routes/ - This folder contains the route definitions for our API.
public/ - This folder contains the static Angular JS 2 files for User Interface.
public1/- This folder contains the assets required for building a login page.
Youtube Link to our Project Video : https://www.youtube.com/watch?v=YWqZcVP687k

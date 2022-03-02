# Getting Started with This Great App #

This project was bootstrapped with [Create React App](https://github.com/johnchristotle/react-redux-mern-stack-app).

## Available Scripts

## 1. Running the React + Redux App Locally ##
Install NodeJS and NPM from 
```https://nodejs.org/en/download/```
Download or clone the project source code from 
```https://github.com/johnchristotle/react-redux-mern-stack-app```
Install all required npm packages by running npm install from the command line in the project root folder ```where the package.json is located```.
Start the application by running npm start from the command line in the project root folder, this will launch a browser displaying the application.


## 2. Running the App with a Real Backend API ##
The boilerplate code uses a fake / mock backend that uses browser local storage for managing application data, to switch to a real backend api you just have to remove a couple of lines of code from the main react entry file (/src/index.jsx).

You can build your own backend api or start with one of the below options:

* To run the auth example with a real backend API built with NodeJS and MongoDB follow the instructions at 
```NodeJS + MongoDB - Simple API for Authentication, Registration and User Management```

* For an API built with NodeJS and MySQL follow the instructions at 
```Node.js + MySQL - Simple API for Authentication, Registration and User Management```

* For a real backend API built with ASP.NET Core 3.1 follow the instructions at 
```ASP.NET Core 3.1 - Simple API for Authentication, Registration and User Management```

## 3. Deploying the React App to AWS EC2 ##
Using the Amazon EC2 (Elastic Compute Cloud) service, deploy the custom MERN Stack application to it, supporting user registration and authentication. 

Steps:
- Create a new Ubuntu server on AWS EC2  
- Connect to Ubuntu EC2 instance via SSH/HTTP 
- Setup server with Node.js + MongoDB + NGINX 
- Deploy Node.js + MongoDB back-end API 
- Deploy React + Redux Front-end app
- Configure NGINX to serve API and front-end 
- Test the MERN Stack app in a browser

## Author

Christotle Agholor (c) 2022

- [GitHub profile](https://github.com/johnchristotle)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributor-shield]: https://img.shields.io/badge/Contributors-1-%2300ff00


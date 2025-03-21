# API Testing using Postman and Newman
Automation excersice with Postman

# Project Overview
This repository contains a Postman collection for API testing of the Automation Exercise website (14 pre-defined sample tests). 
The project is intended to assess API test coverage and functionality of the website's backend services.

# Features
Pre-defined API test collection
Automated API testing scripts
Environment-specific configurations
Informetion on test reporting
CI/CD pipeline 

# Requirements
* Node.js (14.x)
* Postman
* Newman (Optional, for CLI testing)
* Stable internet connection

# Installation
* Clone the Repository
  
git clone https://github.com/arunas-gr/automation-exercise-postman.git

cd automation-exercise-postman

* Postman Import
  
Open Postman

Click "Import"

Select the Postman Collection JSON file

Import Environment Variables

* Install dependencies (if required for Newman execution):
npm install -g newman

# Configuration
* Modify environment variables in Postman
* Update base URL if needed
* Configure authentication credentials

# Running Tests
* Postman GUI
* Open Postman
* Select the collection
* Click "Run" to execute tests

# Run collection
newman run automation-exercise-collection.json

Test Coverage

User Authentication

Product Management

Cart Operations

Order Processing

User Profile Management

# Contributing

Fork the repository

Create the feature branch

Commit changes you made

Push to the branch

Create a Pull Request

# Disclaimer
Tests are created following the tasks, provided on Automation Exercise API website.
Author of this file cannot be held in any way liable for any outcomes of any usage of this code.

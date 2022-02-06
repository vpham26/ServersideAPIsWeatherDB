# ServersideAPIsWeatherDB
***

## Table of Contents
***

1. [General Info](#general-info)
2. [Technologies](#technologies)
3. [Installation](#installation)
4. [Acceptance Criteria](#acceptance-criteria)
5. [Mock Up](#mock-up)
6. [Grading Requirements](#grading-requirements)
7. [How to Submit the Challenge](#how-to-submit-the-challenge)

## General Info
***

This Week Challenge
Third-party APIs allow developers to access their data and functionality by making requests with specific parameters to a URL. Developers are often tasked with retrieving data from another application's API and using it in the context of their own. Your challenge is to build a weather dashboard that will run in the browser and feature dynamically updated HTML and CSS.

*** 

* User Story

AS A traveler
I WANT to see the weather outlook for multiple cities
SO THAT I can plan a trip accordingly
Acceptance Criteria
GIVEN a weather dashboard with form inputs
WHEN I search for a city
THEN I am presented with current and future conditions for that city and that city is added to the search history
WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, the wind speed, and the UV index
WHEN I view the UV index
THEN I am presented with a color that indicates whether the conditions are favorable, moderate, or severe
WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, the wind speed, and the humidity
WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city

## Technologies
***
Use the OpenWeather One Call API (Links to an external site.) to retrieve weather data for cities. Read through the documentation for setup and usage instructions. You will use localStorage to store any persistent data.

## Installation
***

1. Create github repo named ServersideAPIsWeatherDB. Then clone it into local repo.
    
$ git clone git@github.com:vpham26/ServersideAPIsWeatherDB.git

$ git check out develop

work on .js 

$ git add .

$ git commit -m "" (make commits along the process)

$ git push develop

$ git merge master (if there is a develop branch) 

$ git push origin main

2. Modify the code to meet the Acceptance Criteria.

3. Ensure the work meets the full list of grading requirements below.

4. Follow the submission instructions.

## Acceptance Criteria
*** 

GIVEN I need a new, secure password
WHEN I click the button to generate a password
THEN I am presented with a series of prompts for password criteria
WHEN prompted for password criteria
THEN I select which criteria to include in the password
WHEN prompted for the length of the password
THEN I choose a length of at least 8 characters and no more than 128 characters
WHEN asked for character types to include in the password
THEN I confirm whether or not to include lowercase, uppercase, numeric, and/or special characters
WHEN I answer each prompt
THEN my input should be validated and at least one character type should be selected
WHEN all prompts are answered
THEN a password is generated that matches the selected criteria
WHEN the password is generated
THEN the password is either displayed in an alert or written to the page

## Mock-Up
*** 


## Grading Requirements

This challenge is graded based on the following criteria:

* Technical Acceptance Criteria: 40%

Satisfies all of the above acceptance criteria plus the following:

Uses the OpenWeather API to retrieve weather data

Uses localStorage to store persistent data

* Deployment: 32%

Application deployed at live URL

Application loads with no errors

Application GitHub URL submitted

GitHub repository that contains application code

* Application Quality: 15%

Application user experience is intuitive and easy to navigate

Application user interface style is clean and polished

Application resembles the mock-up functionality provided in the Challenge instructions

* Repository Quality: 13%

Repository has a unique name

Repository follows best practices for file structure and naming conventions

Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

Repository contains multiple descriptive commit messages

Repository contains quality README file with description, screenshot, and link to deployed application

## How to Submit the Challenge

You are required to submit BOTH of the following for review:

The URL of the functional, deployed application.

The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.
# Brief-gestion-virus-COVID-19

This app contains 2 parts

Part 1:


The administrator will authenticate in the application


He can consult, add or modify or delete a doctor. (Using MOCK REST API)


Part 2:


A doctor will authenticate himself in the application


He can check the dashboard to see statistics and progress of the Covid-19 virus around the world (using Covid-19 API)


A new patient has come to take the Covid-19 test, the doctor will create a new file containing this patient's information, then he will ask him a set of questions for a diagnosis


After the Covid-19 test automatically a test sheet will be created, and then print its sheet in PDF format


In the event that the patient is positive, the doctor will send an email as a declaration to the authorities from the application (using nodeJS mongoDB)


----------

# Getting started

## Requirements

* Node Js 
* MongoDB

## Installation



Clone the repository

    git clone https://github.com/ABelcaid/covid19-App 
   
   
Go into the repository

    cd covid19-App


First things first you need  to run the node js server 

    cd backend/patient
    

Install all the dependencies using npm

    npm install


To start the express server, run the following
# DreamSpace
A program for listing and finding Professional spaces to rent.

## Basic Functionality
  ### Pages
  * Landing Page
  * Login Page
  * Account Creation Page
  * Search Result Page
  * Individual Rental detail page
  * Rental Listing Creation Page
  * Current Listings Page

#### Landing Page
  * A user will navigate to a website (etc. https://dreamspacerental.com) and they will see a landing page.
  * The Landing page will contain:
    * A button to log in.
    * A Button to Sign Up.
    * A Search box to search for open rentals.
    * A Button to list your space for rent.

## Front-End:
  The front end will be created in React, using Redux in order to connect to the Back-End.  It will be built on a base of shared elements which then send requests to the Back-End API which will be seperate from the Front-End.

## Back-End:
  The Back End will be created in Ruby, which will host the API, calculate all necessary values and elements and send them to the Front-End as responses to API requests.  This will be hosted on AWS as an EC2 instance in a Docker Container.

## Database:
  The Database will be created as a MySQL database that will be hosted on AWS as an RDS cluster, which can easily be accessed from the Back-End.
  
Creators (2021):
  - Wesley Messer
  - Andrew Messer
  - Tyler Crum

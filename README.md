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

#### Login Page
  * A user will be able to enter credentials and login to the system, or be linked to the account creation screen to create a new account
  * The Login page will contain:
    * A Textbox to enter the Username
    * A Texbox (That shows dots instead of what is typed in) to enter the password
    * A Button to login
    * A Small link to the account creation page

#### Account Creation Page
  * A user will be able to create an account by entering in credentials and receive an email to verify their account
  * The Account Creation will contain:
    * A Textbox to enter the Username
    * A Texbox (That shows dots instead of what is typed in) to enter the password (Which will verify in real time if it meets requirements)
    * A Texbox (That shows dots instead of what is typed in) to confirm the password (Which will verify in real time if it matches the first password)
    * A button to create the account

#### Search Result Page
  * A user will be shown all rentals available near where they searched that match the criteria that was entered.
  * The Search Result Page will contain:
    * A Text Box to enter in the search area
    * A Login button on the top right to reach the login screen
    * A Sign Up button next to the login button to create an account
    * A Button to begin the search (That will only search once a criteria is entered)

#### Individual Rental detail Page
  * A user will be able to select a rental they find from their search and see the details of that rental.
  * Details of the rental include:
    * Price
    * Dates Available
    * Size
    * Ameneties
    * Date Listed
    * Location
    * Surroundings

#### Rental Listing Creation Page:
  * A user will be able to easily list their professional space for rent
  * The Rental Listing Creation Page will contain:
    * Text/Selection boxes to input all information for the rental

#### Current Listings Page:
  * A user will be able to view all of the current spaces they have listed for rent, including already rented spaces with a selector to hide those.
  * The Current Listings Page will include:
    * A Card for each listing they have created with the information of that listing
    * A Create New button to create a new listing
    * A Button on each card to delete that listing
    * A Button on each card to pause that listing
    * A Button on each card to mark that listing as rented

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

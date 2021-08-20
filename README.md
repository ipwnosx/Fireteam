# Fireteam

A responsive LFG Website for Destiny 2 made using the MERN Stack + Redux (for application wide state management) and deployed onto a DigitalOcean droplet.
<br>
#### Check it out: https://www.destinylfg.us

###
[![Weekly Users](https://img.shields.io/badge/Weekly%20Users-400+-blue)]()
[![Release](https://img.shields.io/badge/Version-2.0.0-blue)]()
[![Analytics](https://img.shields.io/badge/Analytics-GA-pink)]()
[![Product Maintained](https://img.shields.io/badge/Product%20Maintained-Yes-orange)]()
[![Repo Maintained](https://img.shields.io/badge/Repository%20Maintained-No-red)]() [![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause)

## Previews of v2.0.0
|        |        |
|--------|--------|
|![Home](https://github.com/vrundpat/Fireteam/blob/master/client/src/images/MainPageJumbotronGif.gif)| ![Home](https://github.com/vrundpat/Fireteam/blob/master/client/src/images/LoginPageGif.gif)|
|![Home](https://github.com/vrundpat/Fireteam/blob/master/client/src/images/RegisterPageGif.gif)|![Home](https://github.com/vrundpat/Fireteam/blob/master/client/src/images/CreateModal.png)|
|![Home](https://github.com/vrundpat/Fireteam/blob/master/client/src/images/JoinModal.png)|![Home](https://github.com/vrundpat/Fireteam/blob/master/client/src/images/MainPageScrollGif.gif)|


##
## Technologies Used: 
[![Weekly Users](https://img.shields.io/badge/Framework-NodeJS-blue)]()
[![Generic badge](https://img.shields.io/badge/Database-MongoDB-blue.svg)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/Backend-Express-blue.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/Frontend-React-blue.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/State%20Persistence-Redux-blue.svg)](https://shields.io/)

##
### Note: This repository is limited to v1.0.0. Expect drastic changes in design from the previews above.
###
#### Instructions to run locally:

 1) In the project root:
 ```javascript
    npm install
 ```
    
 2) Client folder ```cd client``` : 
     1) Install Dependencies:
     ```javascript
     npm install
     ```
 
 3) Config Environment Variables:
      1) Create a file named ```.env ```  in the project root (this file maybe be hidden by default by your IDE)
      2) In the ```.env``` file, add the following:
         ```javascript
         DB_URI=YOUR-MONGODB-DB-URI
         JWT_Secret=Your preferred json webtoken secret used for issuing/verifying tokens
         FIRETEAM_TIMEOUT=Time between fireteam creations imposed on the users in milliseconds
         FIRETEAM_DESCRIPTION_LIMIT=Maximum length of the fireteam description field
         BUILD=dev
         ```
  4) From the project root:
     ```javascript
     npm run dev
     ```
  5) Open port ```8080``` in a browser to see a local version of the site! This is not a production build, optimization of the building process is not implemented for this repo.

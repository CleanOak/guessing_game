# Guessing Game

(Developer: Morgan Asare)

[Link to the website](https://worldguessinggame-6a1c3a2b64fc.herokuapp.com/)

![An image previewing all devices](/assets/screenshots/preview.png)

## Table of Content

1. [Project Goals](#project-goals)
    1. [User Goals](#user-goals)
    2. [Site Owner Goals](#site-owner-goals)
2. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Requirements and Expectations](#user-requrements-and-expectations)
3. [Technologies Used](#technologies-used)
    1. [Languages](#languages)
    2. [Frameworks & Tools](#frameworks-&-tools)
4. [Features](#features)
5. [Testing](#validation)
    1. [Application Testing](#performing-tests-on-various-devices)
6. [Bugs](#Bugs)
7. [Deployment](#deployment)
8. [Credits](#credits)
9. [Acknowledgements](#acknowledgements)

## Project Goals
### User Stories

- Be able to sign up as new user
- Be able to login as existing user
- Be able read the rules of the game
- Be able to play a simple game of country guessing game

### Site Owner Goals
- Ensure user is able to create a user account
- Ensure user is able to enter username, email and password
- Ensure user is able to Login with username password already created
- Ensure user can read the instructions before playing the game
- Ensure the game is intuitive
- Ensure user is able to restart the game


## User Experience
### Target Audience

- User is able to create an account 
- User is able to login to the account
- User is able to find the instructions
- User is able to play the game easily

## Technologies Used

## Technical Design 
### Flowchart

- [Lucidchart](https://www.lucidchart.com) was used to build flowchart

<details>
    <summary>Flowchart</summary>
    <p>Hangman Game Flowchart</p>
    <img src = "assets/screenshots/flowchart.png" alt = "A screenshot of flowchart">
</details>

## Language Used
 - Python

## Libraries Used
- os
- random
- re
- gspread
- google

### Other websites/tools used

- [GitHub](https://github.com/) was used for saving and storing files.
- [Heroku](https://www.heroku.com/) was used as the deploying platform for this site.

<details>
    <summary>Hosted App on Heroku</summary>
    <img src="assets/screenshots/logout.png" alt="Game load page">
</details> 

## Features

## Login and SignUp
 - The first page welcomes the user to the game
 - Then User is asked if they already have an account or not
 - User gets a yes or no prompt for the program to proceed

 <details>
    <summary>Home Page screenshot</summary>
    <img src="assets/screenshots/main_screen.png" alt="Game load page">
</details> 

- If user has no account, the no answer takes them to the signup page
- User provides username, email and password
- email is in the format example@address.com

## Game page

- Game page loads once the user username and passwords are validated

 <details>
    <summary>Game Page screenshot</summary>
    <img src="assets/screenshots/game_screen.png" alt="Game load page">
</details> 

## Game starts

- User starts by guessing random letters that might form a country word
- User has 10 tries to guess the correct country

<details>
    <summary>Game Start Page screenshot</summary>
    <img src="assets/screenshots/game_starts.png" alt="Game load page">
</details> 

## Restart Game

- When User finish playin and wins there is a congratulation message
- User is asked if they want to play again

<details>
    <summary>Finish Page screenshot</summary>
    <img src="assets/screenshots/finish_game.png" alt="Game load page">
</details> 

- If they selected yes for restart the game starts 

<details>
    <summary>Restart Page screenshot</summary>
    <img src="assets/screenshots/restart.png" alt="Game load page">
</details> 

- If user decides to end the game by selecting no
- A goodbye message is displayed and prompted the application is logging out

<details>
    <summary>Logout Page screenshot</summary>
    <img src="assets/screenshots/logout.png" alt="Game load page">
</details> 


## Testing

- Manual testing of user stories
- Testing on Browsers
- Tested Devices with Browsers
- Validator Testing

## Deployment

## Deployment

### Deploying the website in Heroku:
- The website was deployed to Heroku using the following steps:
#### Login or create an account at Heroku
- Create a student account on Heroko and login

<details>
    <summary>Heroko Login Page</summary>
    <img src="assets/heroku/heroku_login.png" alt="Heroko login page">
</details>

#### Creating an app
  - Create new app in the top right of the screen and add an app name.
  - Select region
  - Then click "create app".

<details>
    <summary>Create App</summary>
    <img src="assets/heroku/createapp.png" alt="Heroko create app screenshot">
</details>

#### Open settings Tab
  ##### Click on config var
  - Store CREDS file from gitpod in key and add the values
  - Store PORT in key and value

<details>
    <summary>Config var</summary>
    <img src="assets/heroku/config.png" alt="Config var screenshot">
</details>

  ##### Add Buildpacks
  - Add python buildpack first
  - Add Nodejs buildpack after that

<details>
    <summary>Buildpacks</summary>
    <img src="assets/heroku/buildpacks.png" alt="Buildpacks screenshot">
</details>

 #### Open Deploy Tab
   ##### Choose deployment method
  - Connect GITHUB
  - Login if prompted

<details>
    <summary>Deployment method</summary>
    <img src="assets/heroku/method.png" alt="Deployment method screenshot">
</details>

   ##### Connect to Github
  - Choose repositories you want to connect
  - Click "Connect"

<details>
    <summary> Repo Connect</summary>
    <img src="assets/heroku/repo-connect.png" alt="Repo connect screenshot">
</details>

  ##### Automatic and Manual deploy
  - Choose a method to deploy
  - After Deploy is clicked it will install various file

<details>
    <summary> Deploy methods</summary>
    <img src="assets/heroku/deploy.png" alt="deploy method screenshot">
</details>

  ##### Final Deployment
  - A view button will display
  - Once clicked the website will open

<details>
    <summary> Deploy</summary>
    <img src="assets/heroku/view.png" alt="view screenshot">
</details>

## Credits

- The Idea was from Geeks for Geeks [Geeks for Geeks](https://www.geeksforgeeks.org/python-program-for-word-guessing-game/)
- Some of the code was borrowed from [hangman-pp3](https://github.com/Sinha5714/hangman-pp3)
- Also, regex for validating passwords was borrowed from [Tutorialspoint](https://www.tutorialspoint.com/password-validation-in-python)
### Content
- The idea of Guessing Game was taken from other word guessing games played around the world

### Code
#### The following ideas were borrowed from [Love Sandwiches](https://github.com/Sinha5714/Love_Sandwiches)
####

-  validate_user_details function
-  How to import gspread
-  How to import Credentials from google.oauth
- [W3 Schools](https://validator.w3.org/nu/)
- [Stack Overflow](https://validator.w3.org/nu/)
- [hangman-pp3](https://github.com/Sinha5714/hangman-pp3)


## Acknowledgement
- to my mentor Mo Shami for supporting me with his feedback through the entire project
- Special thanks to my friends Amoafo who is always ready to support me on the journey
- Also to my dear wife for beign there for me eventhough I have to abandon some family duties

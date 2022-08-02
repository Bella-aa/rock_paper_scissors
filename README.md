# **ROCK, PAPER, SCISSORS GAME**

## **Game Intro**

A simple rock,paper, scissors game where the user plays against the computer, for people of all ages.

The game website is live on Heroku [Linked Here](https://easy-rock-paper-scissors.herokuapp.com/)

![Screenshot 2022-08-02 092709](https://user-images.githubusercontent.com/103276740/182329211-9fef29c6-98b0-4a66-8214-eaf457e8aa12.png)

## **User Stories**

* As a user, I want the game to be easily accessed.
* As a user, I want the game to be easy to navigate.
* As a user, I want the game to be interesting.
* As a user, I want the game to have clear rules.
* As a user, I want the game to be entertaining.

## **Features**

### **How to play**

#### **Game rules**

* Right at the start when the gaeme loads , the user is introduced to the game rules to continue with the game.

![Screenshot 2022-08-02 093305](https://user-images.githubusercontent.com/103276740/182330283-7111fc58-90c2-4fcb-9cdc-c6ec0f1c253f.png)

#### **Gameplay**

* The user is prompted to choose the option they want. If the user chooses either rock, paper or scissors the game continues and if they choose q the game ends.
* After the user chooses their option between rock, paper and scissors , the user input is compared to the computer pick and a    result showing who won the round is generated, and so on.

![Screenshot 2022-08-02 094029](https://user-images.githubusercontent.com/103276740/182331766-d90f4da3-a2f8-4ba0-9fee-a11b00a3242f.png)

* When the user feel like not playing anymore they can choose the quite option and the game stops showing the number of points the user has won against the computer. The user can then choose to play the game again if they want to.

![Screenshot 2022-08-02 094403](https://user-images.githubusercontent.com/103276740/182332535-1befe7ec-7d98-4ea0-a311-1459c7fff321.png)

## **Testing**

I have manually tested this application by doing the following:

* Passed the code through PEP8 linter and confirmed there is no issues after I fixed the issues indicated on the report.
* Tested in my local terminal and the Code Institute Heroku terminal.

![Screenshot 2022-08-02 094800](https://user-images.githubusercontent.com/103276740/182333371-7edf9857-b77a-47f3-b280-5a0be10f735b.png)

## **Technologies Used**

* [GitHub](https://github.com/) - used for secure storage of code online
* [Python](https://www.python.org/) - Python is used for creating this application
* Heroku for deploying this game

## **Deployment**

This project was deployed using Code Institute's Python mock terminal for Heroku

The steps are as follows:

* Create a new app, by clicking 'New' in the top right section of the welcome page.
* Choose a name for your new application and select your region.
* Go to the Settings tab, and add two buildpacks in this exact order:

1. `heroku/python`
2. `heroku/nodejs`

* Go to 'Deploy' tab and select 'GitHub' as deployment method.
* Locate your repository on 'Github', then select 'connect repository'.
* Chose "Automatic deployment" if you'd like your app to be automatically updated after you do any changes to your code.
* Chose "Manual deployment" if you like to have control when the code is updated to your already deployed app.
* Chose the main branch and click build.

## **Credits**

### **General reference:**

* Besides the course's material I used Youtube for reference to create this project.







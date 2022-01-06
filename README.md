# Code-Quiz
For this project the customer request we:

Build a JavaScript Code Quiz that must contain the following:

Instructions on quiz play
A timer starting when quiz begins
The ability to loop thru multiple choice questions & answers
Statement showing if answer chosen was right or wrong
Time subtracted from incorrect answer selection
The ability to save player initials & top scores
The ability to clear high scores
The ability to view high scores
The ability to go back & retake quiz
Game over presented when all questions answered OR timer runs out
Various buttons
Begin Quiz
View High Scores
Submit
Go Back
Clear High Scores
Site
This quiz was newly created no customer boilerplate provided

HTML | code-quiz 🔗
1. Newly created index.html file with the following
All the <meta>, stylesheet <links> & <script> files and/or libraries necessary
Contained inside the top of the <body> is:
A <h1> with a <div> explaining the rules of the game
A Begin Quiz button
And a View High Scores button
The <main> consists of 3 parts:
A gameCard w/ a <h3> & a <footer> which houses:
A Timer
A card w/ the questions
4 multiple choice options
And notification of right or wrong answer selection
An inputForm which consists of:
The Game Over screen
The player's score
An <input> box for player initials
And a Submit button
A scoreCard w/ a <h3> & a <footer> which houses:
The Top 10 High Scores
A Go Back button
And a Clear High Scores Button
CSS
2. Newly created style.css file with the following
Added the html5doctor.com Reset Style Sheet by Richard Clark
Organized the style.css file alphabetically by element < > then class <.> then id <#>
Create the following groups:
Global, Classes, IDs, & Buttons
JS
3. Newly created script.js file with the following
List of variables
List of eventListeners
List of functions
timer f(x) Sets a timer of 15 seconds per Q
displayQA f(x) Displays the multiple choice Q&A part of the game
compareAnswer f(x) Compares the player's selections & responds w/ Correct or Wrong
getScore f(x) Get the scores from local storage
saveScore f(x) Saves scores to local storage
gameOver f(x) Shows Game Over when the player answers all Q's or time runs out
leaderBoard f(x) Shows the scoreCard section of the game
addToLeaderBoard f(x) Adds players initials & score to scoreCard
removeFromLeaderBoard f(x) Clears the scoreCard when button selected
4. Newly created questions.js file with the following
An array which contains an object with the keys of: question, selection & answer
NOTE: The question array can be modified to meet the clients needs at any time

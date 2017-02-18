# Hangman-Game
# HW - {Hangman-Game}

## Live Link (If relevant)
- www.example.com

## Description on how to use the app
- You're the "new guy" at work and will need to guess your co-workers names!  Get them wrong and you'll be fired!'"'

## Requirements

1. [Watch the demo](hangman-game-demo.mov).

2. Choose a theme for your game! In the demo, we picked an 80s theme: 80s questions, 80s sound and an 80s aesthetic. You can choose any subject for your theme, though, so be creative!

3. Use key events to listen for the letters that your players will type.

4. Display the following on the page:

* Press any key to get started!

* Wins: (# of times user guessed the word correctly).

* If the word is `madonna`, display it like this when the game starts: `_ _ _ _ _ _ _`.

* As the user guesses the correct letters, reveal them: `m a d o _  _ a`.

* Number of Guesses Remaining: (# of guesses remaining for the user).

* Letters Already Guessed: (Letters the user has guessed, displayed like `L Z Y H`).

5. After the user wins/loses the game should automatically choose another word and make the user play it.

## Technologies Used
- Javascript for game functionality. 
- HTML for structure.
- Minimal CSS, google fonts. 

## Code Explaination
function startGame(){
- select random word x
- replace letters with underscores
- add underscores to HTML doc
- numguesses === 8, blankandsuccess is an empty array, and wronggueses is empty array

function checkLetters(letter){
- matching user selection to letters in word
- conditional statement.  if letter picked, else not picked
- else will decrease the numGuesses variables by 1.

function roundComplete(){
- update the HTML with letters that are in the word, remaining guesses, wrong guesses
- determine win or lose

document.onkeyup = function(event){
- passing the selected letter through the CheckLetter function 


-------------

```

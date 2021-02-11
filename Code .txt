var guessNumber = 8;

var enterYourGuessedNumber = prompt("Guess a number");

var enterYourGuessedNumber = Number(enterYourGuessedNumber);

if (enterYourGuessedNumber === guessNumber){
    alert("wow! you guessed correct");
}
else if (enterYourGuessedNumber > guessNumber){
    alert("you guess to high");
} 
else if (enterYourGuessedNumber < guessNumber){
    alert("you guess to low");
} else {
    alert("Sorry try next Time");
}
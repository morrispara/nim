 /* NIM simple by Galloway */

/* Global Variables */
var games = 0;
var again = true;
var count = 0;
var turns = 0;
var games = 0;
var next = 
/* Main */
while again==true{
	while count<21{
		if (next = 0){
			turn = cpuTurn();
			alert("computer counts up to " +turn)";
			count+=turn;
		}
		else if (next!=0){
			userTurn();
			count+=turn;
		}
	}
	declareWinner();
	again = playAgain();
	if playAgain=false break;
}
	else if playAgain=true alert("time for a new game!");

	
	
	
/* Functions */

function userTurn(){
	turn = prompt("the count is " +count+ ". How many do you want to count up? (1-3)");
	return Number(turn);
}
function cpuTurn(){
	turn=Math.floor(Math.random()*3)+1;
	return turn;
}

function playAgain(){
playAgain = prompt("Play again? y for yes");
	if playAgain==("y"){
		return true;
	}
	else {
		return false;
	}
}

function declareWinner(next){
	if (next==0){
		alert ("You win!");
	}
	else if (next!=0){
		alert ("You lose!");
	}
}

function nextSwitch(next){
	if (next==0){
		return 1;
	}
	else if (next==1){
		return 0;
	}
}




//nim-simple.js

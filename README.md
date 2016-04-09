# Blackjack

CSC 280 - Assignment Three

Problem One:

1. Implement one class called Card, which is a poker card that has face value and a suit type, and this class also allows you to randomly draw a card. 

2. Implement a Game class, with the main method that implements the following game and winning policy: 

	a. Assume there are two players, and you will act for both Player 1 and Player 2 to input from the keyboard. 

	b. Draw one random card for Player 1, and tell him the card face value, and then provide two options to Player 1: 1. Draw again; 2. Stop. If Player 1 decides to draw again, draw another card, and then present the same two options and the current summation of cards’ face value, until Player 1 selects “Stop”.

	c. Draw one random card for Player 2, then tell him the card face value, and then provide two options to Player 2: 1. Draw again; 2. Stop. If Player 2 decides to draw again, draw another card, and then present the same two options and the current summation of card’s face value, until Player 2 selects “Stop”.

	d. After both players finish, announce the winner with the following rule:
		a. Do a summation of all the cards’ face value of Player 1, say Sum1;
		b. Do a summation of all the cards’ face value of Player 2, say Sum2;
		c. If both Sum1 and Sum2 are less than 21, whichever is closer to 21 wins;
		d. If both Sum1 and Sum2 are larger than 21, tie;
		e. If one of Sum 1 and Sum2 is larger than 21, and the other is lower than 21, the lower one wins.

Requirement:
1. Make sure your code is clearly indented. 2. Make constructor, setter/getter, service method of Card class are provided.

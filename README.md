
# Blackjack Game Project


## Objective:I have Created a console-based Blackjack game where a player can play against the computerized dealer.

Game Rules:
The game will be played with a standard deck of 52 cards.

Face cards (King, Queen, Jack) are worth 10 points each.
Number cards are worth their face value.

Aces can be worth either 1 or 11 points, depending on which value benefits the player.

The goal is to have a hand value as close to 21 as possible without exceeding it.

If a player's hand exceeds 21, they bust and lose the game.

The dealer must hit until their hand value is at least 17.

Game Flow:
The game starts with the player and the dealer each being dealt two cards.

The player can see one of the dealer's cards.

The player can choose to "hit" (receive another card) or "stand" (keep their current hand).

The dealer's turn begins after the player stands.

The dealer reveals their second card.

The dealer hits until their hand value is at least 17.

The winner is determined based on the hand values.

The game ends, and the player can choose to play again.

Implementation Guidelines:
#Deck Representation:
Represent the deck as an array or a list of cards.
Use a function to shuffle the deck at the beginning of each round.

#Card Class:
Create a class to represent a card with attributes like rank and suit.

#Player Class:
Create a class to represent a player with a hand of cards.
Implement functions for adding a card, calculating hand value, and displaying the hand.

#Game Logic:
Implement functions for dealing cards, player's turn, dealer's turn, and determining the winner.
Handle the special case of the Ace being worth 1 or 11 points.

#User Input:
Allow the player to input their decisions (hit or stand) during their turn.
Validate user input to ensure it's a valid option.
Display:

Print the current state of the game after each turn to the console.
Display the winner and the final hands at the end of each round.

#Game Loop:
Implement a loop to allow the player to play multiple rounds.

#Error Handling:
Include error handling for unexpected inputs or invalid moves.
## ![Capture](https://github.com/Suru7deshmukh/Blackjack-Game-Project-/assets/111905703/d6cdd92d-d1fb-47d6-b144-aad67d21ef34)






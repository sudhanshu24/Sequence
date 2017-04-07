# Sequence
Online Implementation of the game with the same name

Basic Game Setup: 
There are 2 decks of cards (minus the Js). That makes it 52x2 - 8 = 104 - 8 = 96 cards.
The cards are organised on a matrix of 12x8. (This order can be random or fixed)

There is a deck of cards, total of 104 cards. Out of these, 8 are the Js which were not counted eatlier. The Js are of two kinds : One Eyed and Two Eyed. They serve different functions, which would be explained below. Rest 96 cards are the same cards that are on the matrix. Thus, its easy to see that there are two instances of each card, for example say the 2 of hearts appears twice in the deck of cards and also twice on the matrix of the game.

In addition to this, we need either 2/4/6/8 players, organised in teams of two sitting across from each other. Each player is given random 5 cards to start with from the deck of cards.

GamePlay:
Players play once each turn, going in clockwise direction.
As a part of each turn, a player does the following:

1) Play a card from the cards in hand:
  Choose a card from your hand and show it to other players. If its not a J, there will be two possible places on the board for this card.   If there is an empty cell (cell without a coin on it), then put one coin of your team's color on that cell, and discard the card
  
  If this card is a J, then :
  a) If its a on eyed J, then choose any one coin on the board and discard the coin
  
  b) If its a two eyed J, then choose any empty cell on the board and keep a coin of your color on the cell.

2) Take a card from the pile of cards if there are any.

3) Discard a card from hand if there is no place to play a card.

Goal of the game is to create a sequence of at least 5 coins of the same color in the same line.
A line may be horizontal, vertical or diagonal. The first team to make 2 separate sequences wins.

The task is to create a website that shows the result of a round of blackjack.
The rules of the game are as follows: Two players, you and Magnus, will play
against each other! Each player takes two cards each from the top of a randomly
shuffled deck. You take the first two cards, Magnus takes the next two Calculate
the total score of each player Numbered cards have points as indicated on the
card Jack (J), Queen (Q) and King (K) count as 10 points Ace (A) counts as 11
points Calculate if one of the players has 21 points - Blackjack - with their
initial card, thus winning the round If no one has 21 points, the players must
draw cards from the top of the deck You must stop drawing cards when the score
reaches 17 or higher You lose the game if the score is higher than 21 When you
have stopped drawing cards, Magnus starts drawing cards Magnus stops drawing
cards when his score is higher than your score Magnus loses the game if the
score is higher than 21 The display of the result must contain: Who won the game
The score and cards of each player at the end of the game. The website should
make it possible to change the end point the deck is taken from, and it should
have a button to play a new round. The answer must contain tests, and the
solution must be universally designed. 🃏 Deck of cards The deck can be found at
https://blackjack.ekstern.dev.nav.no/shuffle. The format of the deck is a
jsonarray with 52 elements, where each element is an object with the fields suit
and value. suit has one of the values ["HEARTS","DIAMONDS","SPADES","CLUBS"]
value has one of the values ["2","3","4","5","6","7","8","9","10","J","Q","K","
A"] ✅ Delivery As a private git

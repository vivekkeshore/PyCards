# Python Card Game - PyCards

## Deck Composition (54 cards)

1. **Primitive Types** (11 cards)
   - Int (x3) - 1 point
   - Float (X3) - 1 point
   - String (x3) - 2 points
   - Bool (x2) - 1 point


2. **Data Structures** (12 cards)
   - List (x3) - 2 points
   - Tuple (x3) - 3 points
   - Dictionary (x3) - 4 points
   - Set (x3) - 4 points


3. **Keywords** (27 cards)
   - if (x3) - 3 points
   - elif (x2) - 3 Points
   - else (x2) - 3 Points
   - try (x2) - 4 Points
   - except (x2) - 4 Points
   - finally (x2) - 4 Points
   - for (x2) - 5 points
   - while (x2) - 5 points
   - def (x2) - 6 points
   - return (x2) - 4 points
   - yield (x2) - 5 points
   - with (x2) - 5 points
   - break (x1) - 4 points
   - raise (x1) - 4 points


5. **Special/Trump Cards** (4 cards)
   - Comprehension (x2) - 6 points
   - Placeholder/Joker (x2) - Flexible

## Games

### Python Card Game - Multiplayer (2-6 players)
#### Minimum Players- 2

**Objective**: The player aims to combine the set of cards dealt to them to form a valid card combination.

**Setup**:

1. Shuffle the deck of cards and deal all the cards equally to the players one by one. If there are 4 players, then each player would get 13 cards. The dealer keeps the remaining cards as the discarded pile.
2. Every player should get same number of cards.
3. The discarded pile will not take any part in the game.

## **Gameplay**:

### **Player's Turn**: 

#### Rules:
- Each player will play in a clockwise direction.
- A player has to make a combination of cards using the cards in hand.
- The player can make a combination of cards using 3 or more cards.
- Once all players have made a combination of cards, and played their hand/round, the player with the highest score takes the hand.
- The player with the highest score starts the next round.
- The game continues till one of the player exhausts all the cards in hand.
- If the player is left with only 3 cards in hand, and if the combination is not possible, then each card will be considered as one point each.
- If the player is left with only 2 cards in hand, then each card will be considered as one point each.


## **Winning**:
The game ends when one of the players exhausts all the cards in hand. Add the score of each hand for each player. The player with the highest score wins the game. 


## Combination Examples
 - Some of the cards have a "pairs with" section. It can be used to create a combination of cards.
 - Example, try + except + finally + else or for + break + else
 - Logical combinations are allowed. Example, if + elif + else
 - Same cards are also allowed for a combination. Example, if + if + if


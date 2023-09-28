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

**Objective**: The player aims to construct valid Python statements or short code using the cards dealt to them while the dealer tries to make it challenging.

**Setup**:

1. Shuffle the deck of cards and deal 5 cards to each player. The dealer keeps the remaining cards as the draw pile.

## **Gameplay**:

### **Player's Turn**: 

#### The player can take only one of the following two actions:
1. Make a Python program or complete statement using 2 or more than cards.
   - Example, if you have an "int" card, a "for" card and a "def" card, then the player can say that the statement created is "def function_name(): for i in range(num): print(i)
   - If the statement is valid, then the player scores a point. The score is equal to the sum of the points of the cards used to make the statement.
   - Try to create more complex statements using more cards to score more points.
   - The statements is up to the player's imagination, but it should be valid.
   - Any statement cannot be repeated by the same or other player.
   

2. If the statement is invalid, or if the player cannot make any statements using the cards in hand, then the player has to pick only one card from the draw pile.


## Other Rules

- Once the player has made a statement or picked a card, the turn passes to the next player.
- If the draw pile is exhausted, then the dealer shuffles the discarded cards that were used to create Python statements and forms a new draw pile.
- The dealer can also shuffle the discarded cards if they feel that the draw pile is too small.
- If a player cannot make a statement using the cards in hand, then they have to pick a card from the draw pile. A player cannot pick the cards from the discarded cards that were used to make Python statements by self or other players.

## **Scoring**:

- The player scores a point for every valid Python statement they form.


## **Winning**:
The game must continue till all the cards from any one of the player's hand are over. The player with the highest score wins.



**Note**: The game requires both players to have a basic understanding of Python syntax. It promotes strategic thinking and a deeper understanding of how Python statements can be constructed.


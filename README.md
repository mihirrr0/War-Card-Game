# Card War Game

The **Card War Game** is a Python implementation of a classic two-player card game where players engage in thrilling card battles and face off in strategic "WAR" scenarios. This game provides an exciting way to experience the dynamics of card comparisons, luck, and decision-making.

## Game Overview

The Card War Game brings the excitement of a traditional card game to your Python environment. In this game, two players are dealt half of a shuffled deck each, and they take turns drawing cards. The player with the higher card value wins the round, collecting both cards. However, when the drawn cards are of equal value, a thrilling "WAR" situation arises, demanding players to draw more cards and engage in a battle of chance and strategy.

## Classes

### Card Class

- Represents an individual playing card.
- Attributes: `suit`, `rank`, and `value`.
- Provides a human-readable string representation.

### Deck Class

- Represents a deck of playing cards.
- Methods: `shuffle_deck()`, `deal_one()`.
- Creates, shuffles, and deals cards from the deck.

### Player Class

- Represents a player in the game.
- Attributes: `name`, `all_cards`.
- Methods: `add_one(new_cards)`, `remove_one()`.
- Handles adding, removing, and displaying cards for a player.

## How to Play

1. Players are initialized with half of the shuffled deck each.
2. Rounds progress with card comparisons; higher value wins, leading to card accumulation.
3. "WAR" situations occur when tied, requiring players to draw more cards.
4. The game continues until a player wins by obtaining all cards or the other runs out.

## Getting Started

1. Clone this repository.
2. Run the provided Python code in a Jupyter Notebook or preferred Python environment.
3. Observe the rounds, wars, and final outcome printed in the console.


Enjoy the Card War Game, where every drawn card could turn the tide of victory!

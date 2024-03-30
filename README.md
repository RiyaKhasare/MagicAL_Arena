# Magical Arena Game

## Overview
This is a simple text-based game implemented in Java where two players battle in an arena until one of them loses all their health.

## How to Run
1. Open Eclipse IDE.
2. Create a new Java project or import the provided `MagicalArena.java` and `TestMagicalArena.java` files into an existing project.
3. Compile and run the `MagicalArena.java` file to start the game.

## Game Rules
- Each player has health, strength, and attack attributes.
- During each round, both players roll a dice to determine their attack and defense values.
- The damage is calculated based on the attack and defense values, and the defender's health is reduced accordingly.
- The game continues until one of the players loses all their health.

## Implementation Details
- The `MagicalArena` class contains the main game logic and the game loop.
- The `Player` class defines the attributes and methods for each player, such as health, strength, attack, and damage calculations.
- The `playRound` method is used to simulate each round of the game where each player attacks and defends.
- The `rollDice` method is used to simulate dice rolling to determine attack and defense values.

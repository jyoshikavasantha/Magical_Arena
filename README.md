# Magical_Arena

## Overview
Magical Arena is a Java simulation where two players engage in combat using three key attributes:
- *Health*: Determines how much damage a player can sustain.
- *Strength*: Impacts the damage a player can inflict.
- *Attack*: Affects the player's ability to hit the opponent.

The simulation reads matchups from a text file and uses randomness to determine the outcomes of fights.

## File Structure
- MagicalArena.java: Contains the main class and methods for simulating battles.
- test_cases.txt: A text file listing pairs of players with their attributes formatted as "Player1Name,Health,Strength,Attack;Player2Name,Health,Strength,Attack".

## Code Explanation
- *Main method*: Reads the test_cases.txt file and processes each line to simulate a duel between two players.
- *Player class*: Stores attributes and methods related to a player.
- *simulateFight()*: Method where two players fight until one loses all health. Results are determined by random dice rolls influenced by player attributes.

## Usage
1. Compile: javac MagicalArena.java
2. Run: java MagicalArena

Ensure the test_cases.txt is in the same directory as MagicalArena.java.

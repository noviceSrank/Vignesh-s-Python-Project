# Vignesh-s-Python-Project
My very first Python projects :)

# Rock paper scissor game: GAME#1
"""# Rock Paper Scissors

A simple two-player command-line game. Each player chooses `scissor`, `paper`,
or `rock` to play a round. Choices are case-insensitive.

## How to play

Run this Python file, then enter a choice when prompted for each player.
Matching choices result in a draw; the round winner earns one point. The first
player to reach 3 points wins. Invalid choices are rejected.

The game uses Python's built-in `input()` and requires no additional packages.
"""


# Parking lot system game: 
# Parking Lot System

'A simple Python command-line program for managing parking spaces, vehicle occupancy, and parking fees.'

## Features

'''- Park and remove two-wheelers (`2w`) and four-wheelers (`4w`).
- Track parking availability across Basement, Ground, 1st, 2nd, 3rd, and 4th floors.
- Restrict two-wheelers to the 3rd and 4th floors.
- Calculate a fee using the selected floor's hourly rate.
- Display the current occupancy status.'''

## Parking rates

'''| Floor | 2-wheelers | 4-wheelers |
| --- | ---: | ---: |
| Basement | Not available | $10/hour |
| Ground | Not available | $12/hour |
| 1st | Not available | $15/hour |
| 2nd | Not available | $18/hour |
| 3rd | $45/hour | $20/hour |
| 4th | $55/hour | $25/hour |''' 

'Each available vehicle-type area has 8 spaces. The configured 2nd-floor 2-wheeler rate is $0, but its capacity is 0, so it is unavailable.'

## Requirements

'- Python 3'

## Run

'Save the original program as `parking_lot.py`, then run:'

'```bash'
'python parking_lot.py'
'```'''

## Menu

'1. **Park Vehicle:** Enter `2w` or `4w` and a floor.'
'2. **Remove Vehicle:** Enter the vehicle type, floor, and number of hours to calculate the fee.'
'3. **Show Status:** Display occupied and total spaces on each floor.'
'4. **Exit:** Close the program.'

## Notes

'' 'Occupancy is held in memory and resets when the program exits. The removal flow asks for the number of hours; the program does not record arrival times.'''

RPS GAME WITH A COMPUTER:
# Rock Paper Scissors Game
#
# A simple beginner-friendly Python game where you play against the computer.
#
# Description
# This project lets the player choose one of three moves:
# - Rock
# - Paper
# - Scissors
#
# The computer makes a random choice, and the winner of each round is decided by the classic rules:
# - Rock beats Scissors
# - Paper beats Rock
# - Scissors beats Paper
#
# The game tracks the score and ends when either the player or the computer reaches 3 points.
#
# How to Play
# 1. Run the Python script.
# 2. Enter one of the following choices:
#    - rock
#    - paper
#    - scissor
#    - quit
# 3. The computer will choose randomly.
# 4. The round result will be shown, and the score will update.
# 5. The game ends when either side reaches 3 points.
#
# Example
# Choose rock, paper, or scissor (or type quit): rock
# Computer chose: scissors
# You win this round!
# Score -> You: 1 | Computer: 0
#
# Features
# - Easy to understand code
# - Random computer moves
# - Score tracking
# - Game ends when someone reaches 3 points
# - Input validation for invalid choices
#
# Requirements
# - Python 3.x
#
# Project Goal
# This game is designed as a basic practice project for learning Python,
# conditionals, loops, dictionaries, and user input handling.

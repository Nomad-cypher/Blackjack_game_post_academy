# Blackjack_game_post_academy

A simple game of Blackjack played using the console

## Description

This is a simple game of Blackjack made in Python you can play in your console. Play against an automated dealer and use letter commands to choose whether to hit or stand during a round.

## Purpose
This is an updated version of the first project I made at Specialisterne Academy. I decided to privatize the old version, and this version of the game continues with the code where the old verison left of. My main goals with the development this updated version is:
1) Update the README to include more detail based on a template provided by SPAC
2) Allow the script to run in Docker
3) Make use of GitHub actions in the development

At the time of writing, there are no plans to update the codebase of the game itself, but I will not rule out code updates or feature additions in the furture

## Getting Started

### Dependencies

Python

### Running the game, in increasing order of complexity

#### Directly from the file

1. Download the file 'Blackjack.py'
2. Run the file (you may need to use 'Open with' > 'Python' if you OS opens it with your code editor by default)

#### In your terminal or code editor

1. Download the file 'Blackjack.py'
2. Open your terminal or code editor and navigate to the folder containing the file
3. Run the following command in your terminal:
```bash
python Blackjack.py
```

#### In Docker

1. Download the files 'Blackjack.py' and 'Dockerfile' and put them in a folder
2. Make sure no other files are in the same folder
3. Make sure that Docker is running
4. Open a terminal and navigate to the folder containing the 2 downloaded files
5. Enter the following commands:
```bash
docker build -t blackjack_game .
```
```bash
docker run -it blackjack_game
```

### Playing the game
It is assumed that you're already familiar with the normal rules of Blackjack

* Start the game by running the script. The game is played using a single deck of cards and the deck is reset between each round. Each round is played inderpendently from all other rounds.
* When starting the game, you will be informed of the dealers hand and your own starting hand and points. You may need to increase the height of your console window if you see no information about the dealers hand.
* When prompted, enter `h` into the console to draw another card (hit) or `s` to stop drawing and pass the turn back to the dealer (stand). The dealer will then draw until they have at least 18 points and you will then be informed whether you win, lose, or if it's a draw.
* When the game is over, you can enter `y` into the console to play again, entering anything else exits the game.

## Help

* When playing, you should only use lowercase single letters when entering commands into the console
* If you do not see any information about the dealer's hand when starting the game, increase the height of your console window

## Author

@Nomad-cypher

## Acknowledgments

Thanks to SPAC (Specialisterne Academy) for:
* The initial exercise that created the first version of the game
* Providing the template this README is based on
* Setting time aside during the Academy for us to make improvements on previous projects :)
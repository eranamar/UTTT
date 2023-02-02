# Ultimate "Ultimate Tic Tac Toe" Player

This was the final project in AI course at HUJI (winter 2013/14).

## Authors 
Adi Ben Binyamin & Eran Amar.

## Subject
Adversarial Search - Minimax and optimizations.

## About the project
Ultimate Tic Tac Toe (<abbr title="Ultimate Tic Tac Toe">UTTT</abbr>) is a nested version of the regular Tic Tac Toe (<abbr title="Tic Tac Toe">TTT</abbr>) game. It is a 2-players zero-sum game, which includes a matrix of 3x3 boards of TTT (_mini boards_). Each mini-board is an independent Tic Tac Toe game. To win a game, a player must win three mini boards in a row. Each player may only play inside a mini-board that corresponds to the cell that its opponent played the last turn. The player who start the game is free to choose any cell. In addition, when a player is sent to a mini-board that is already decided (and therefore all its cells are "disabled") may choose any free cell in any non-decided mini-board, such a move called a _wildcard_.

The main target of our project is to build an ultimate UTTT player that will have both high winning rate and chooses a move in a reasonable amount of time (on average).

## Usage 
```
python uttt_game_engine.py <agent1> <agent2>
```

For example: 
```
python uttt_game_engine.py MM_Winning human
```

Run with no arguments to see the full agents list.

See the full report PDF under the repo's folder.


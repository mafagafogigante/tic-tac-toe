# Tic-tac-toe

This repository contains AI implementations for the popular paper-and-pencil
game known as Tic-tac-toe. There is also a GUI-based game that allows the user
to play against the computer. [There is also a blog post about this project]
(http://www.bernardosulzbach.com/tic-tac-toe-using-racket/).

# Racket Code

You will need, as you may assume, a Racket distribution in order to run the
Racket programs.

Running the interactive game will allow you to play against the computer.

This should be as simple as

```bash
$ racket game.rkt
```

<p align="center">
  <img src="http://i.imgur.com/yLMuDUv.png" alt="Game Screenshot">
</p>

The algorithm is a naïve implementation of minimax.

# Continuous Integration Status

[![Build Status](https://travis-ci.org/bernardosulzbach/tic-tac-toe.svg?branch=master)](https://travis-ci.org/bernardosulzbach/tic-tac-toe)

Travis CI provides continuous integration for this project. The badge on this
section presents the build and test status of the master branch.

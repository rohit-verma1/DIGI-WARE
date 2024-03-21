# Tic-Tac-Toe Game in Verilog

This is a simple implementation of the classic Tic-Tac-Toe game using Verilog hardware description language (HDL).

## Overview

Tic-Tac-Toe is a two-player game where each player takes turns marking spaces on a 3x3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.

## Features

- **Two-player gameplay:** Supports two players taking turns to make moves.
- **Game state tracking:** Keeps track of the current state of the game, including the positions of X and O marks on the grid.
- **Win detection:** Detects when a player has won the game by forming a line of three marks in a row, column, or diagonal.
- **Draw detection:** Detects when the game ends in a draw if all spaces on the grid are filled without a winner.
- **Reset functionality:** Allows the game to be reset to start a new round.

## Files

- `tic_tac_toe_game.v`: Verilog code for the Tic-Tac-Toe game module.
- `tb.v`: Test Bench for the Verilog code

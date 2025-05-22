CSC 4444

A Texas Hold'Em poker game in Python

by Patrick Adeosun, Kendall Comeaux, Tristan Evans, John Gravois, Olabode Ige, Matthew Mccoy, Austin Mestayer, Kohl Morris, Vaughn Ohlerking, Trevor Spinosa

Poker.py is the game engine and deck/player generator.

Handles side pots

imported modules:

Pokerhands.py is a hand evaluator and scoring tool, takes a value (1-13) of individual cards in a player's hand and returns a score, including facility for tie-breaks/split pots

Pokerstrat.py is a module that allocates player strategies; currently has one AI that plays at random, a Human (needs keyboard input), and one other

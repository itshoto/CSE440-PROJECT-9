# CSE440-PROJECT-9
# Adventure Quest: Probabilistic Text-Based Game Using Factor Graphs

## Overview
This project implements a simple text-based adventure game where player decisions update a factor graph model via belief propagation. The game tracks probabilistic states (Health, Wealth, Reputation, Danger) across four scenes, providing nuanced outcomes based on inferred marginals.

Designed for beginners to explore probabilistic graphical models (PGMs) in a fun context.

## Features
- Factor graph engine with unary/pairwise factors and loopy BP.
- 4 scenes with branching choices.
- Probabilistic narratives and stochastic events.
- Save/load game state.

## Installation
1. Clone the repo: `git clone https://github.com/itshoto/CSE440-PROJECT-9.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run: `main.ipynb` or `main.py` (extract script).

## Usage
Run the main loop: Make choices (1-3), view probabilistic outcomes. Use 's' to save, 'l' to load, 'q' to quit.

Example Output:
 High health in safe surroundings after safe choices.

## Code Structure
1. `FactorGraph` class: Core PGM implementation.
2. `build_default_graph()`: Sets up variables/factors.
3. `SCENES`: List of game scenes with effects.
4. `main_game_loop()`: Interactive loop.

## Dependencies
See requirements.txt.

## Acknowledgments
Inspired by PGM tutorials [references in report].

## License
MIT License.

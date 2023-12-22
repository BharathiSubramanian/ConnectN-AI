# Connect-N AI with Minimax and Alpha-Beta Pruning

## Overview

In this project, we implemented a Connect-N AI using the Minimax algorithm with Alpha-Beta pruning. This enhanced the classic Connect 4 game by introducing the goal of connecting N discs. The methods involve tree traversal, maximizing and minimizing player strategies, terminal node evaluation, and Alpha-Beta pruning. We explored parameters such as width, height, and N, influencing game dynamics, and incorporated heuristics for effective decision-making. Despite some limitations, the artificial intelligence [AI] demonstrates strategic gameplay in Connect-N.

## Key Features

- Connect-N AI implementation with Minimax and Alpha-Beta pruning
- Goal: Connect N discs, enhancing the classic Connect 4 game
- Tree traversal, maximizing and minimizing player strategies
- Terminal node evaluation and incorporation of heuristics
- Exploration of parameters like width, height, and N

## Usage

### Analysis of various ConnectN-AI algorithms

1. Clone the repository.
2. Each different .py file with the connectn prefix has a different approach to the problem and performs well in specific board sizes.
3. Explore and adjust parameters for different game dynamics.

### Connect-N Game Simulation

This is a program to simulate multiple games of Connect-N between two teams (Team A and Team B) and tracks the number of wins for each team along with draws.

#### Requirements

- Python 3.x (Should be compatible with `random`, `time`, `sys` and `math` libraries.)

#### Setup

1. Extract all the files in ConnectN-Simulation.zip into a file directory.

2. Navigate to the project directory:

   ```bash
   cd $(file directory)
   ```

3. Install required dependencies:

   ```bash
   pip install numpy
   pip install pygame
   ```

   Note: PyGame is only needed if you are looking to run a GUI simulation of the game.

#### Running the Simulation

1. Open a terminal and navigate to the project directory.

2. Run the simulation:

   ```bash
   python gameloop.py
   ```

3. The program will simulate multiple games (as specified by `NUM_GAMES` in `gameloop.py`) between Team A and Team B on a Connect-N board.

4. The results, including the number of wins for Team A, draws, and wins for Team B, will be displayed at the end of the simulation.

#### Customization

- You can modify the parameters such as `width`, `height`, and `n` in `main.py` to customize the size of the game board and the winning condition.

- If you want to modify the behavior of Team A or Team B, you can edit the files `team_A.py` and `team_B.py` respectively.

## Limitations

- This project was taken as a challenge with a specific constraint to have no ML-based learning techniques to learn the opponent's moves and only rely on AI search algorithms. This is a bottleneck to the performance of the model.
- The different approaches in the model were implemented with a constraint on the time taken by the agent to play its move so that during simulation, the agent is not too slow. This is a roadblock for us from trying algorithms which searches deeply.

## Contributions
- Feel free to contribute ideas and if they are more efficient and are obeying the constraints measures, the contribution will be added to the repository.

## Thank you.

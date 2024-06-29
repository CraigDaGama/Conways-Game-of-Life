# The Game of Life

The Game of Life, devised by mathematician John Conway in 1970, is a cellular automaton played on a two-dimensional grid of square cells. Each cell can be in one of two states: alive or dead. The state of the grid evolves over discrete time steps according to a set of simple rules, applied simultaneously to all cells.

## Rules

1. **Underpopulation**
   - A live cell with fewer than two live neighbours dies.
2. **Survival**
   - A live cell with two or three live neighbours remains alive.
3. **Overpopulation**
   - A live cell with more than three live neighbours dies.
4. **Reproduction**
   - A dead cell with exactly three live neighbours becomes alive.

The Game of Life is known for its capacity to produce complex, often unpredictable patterns from simple initial states. Despite its simplicity, the game demonstrates how complex behaviors and structures can emerge from basic rules.

## Controls

- **Mouse Click:** Toggle the state of a cell (alive or dead).
- **Space Bar:** Start or pause the game.
- **C Key:** Clear the grid and reset the game.
- **G Key:** Generate a random configuration of cells.

## Installation

1. Ensure you have Python installed on your system.
2. Install Pygame by running the following command:
    ```bash
    pip install pygame
    ```

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/CraigDaGama/game-of-life.git
    cd game-of-life
    ```
2. Run the game:
    ```bash
    python game_of_life.py
    ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

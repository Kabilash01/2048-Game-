
# 2048 Game

This is a simple implementation of the popular 2048 sliding tile puzzle game. The objective of the game is to combine tiles with the same value to create a tile with the number 2048 (or higher!). The game takes place on a 4x4 grid, where you can move the tiles up, down, left, or right to merge them.

## Features

- **Tile Merging**: Merge two tiles with the same number to form a new tile with double the value.
- **Random Tile Generation**: After each move, a new tile (2 or 4) appears at a random empty location on the grid.
- **Score Tracking**: Keep track of your score as you merge higher-value tiles.
- **Win Condition**: The game is won when a tile with the value of **2048** is created.
- **Game Over Detection**: The game ends when no more valid moves can be made on the board.
- **Restart Option**: Restart the game at any time.

## How to Play

1. **Controls**: Use the arrow keys on your keyboard to slide the tiles in the desired direction.
   - **Up**: Move all tiles up.
   - **Down**: Move all tiles down.
   - **Left**: Move all tiles left.
   - **Right**: Move all tiles right.
2. **Objective**: Combine tiles with the same number to form larger numbers until you create the **2048** tile.
3. **Game Over**: If the grid is full and no more moves are possible, the game ends.

### Example Gameplay

```plaintext
[2]  [2]  [4]  [8]
[16] [32] [64] [128]
[256] [512] [1024] [ ]
```

- Move the tiles using the arrow keys.
- Merging two `[2]` tiles creates a `[4]`.
- The goal is to create the **2048** tile!

## Project Structure

```
2048-Game/
│
├── src/                      # Source code for the game
├── assets/                   # Game assets like images or sounds (optional)
├── README.md                 # Project documentation
└── .gitignore                # Ignore compiled files and unnecessary items
```

## Installation

To run the game locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Kabilash01/2048-Game.git
   cd 2048-Game
   ```

2. Depending on your platform and language of implementation, run the game:
   - If it’s implemented in Java, Python, or JavaScript, use the respective commands to compile and run it.

## Contributing

Contributions are welcome! If you want to add new features or fix bugs, follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact

For any inquiries or issues, feel free to reach out to [Kabilash01](https://github.com/Kabilash01).
```


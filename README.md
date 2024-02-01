# Blockr

### Terminology
- Board: A grid of cells where the game is played. The board is 10 cells wide and 20 cells tall.
- Tetromino: A shape made up of four squares. Each square occupies a cell on the game board.
- Frame: A snapshot of the game board at a given point in time. ie what spaces are occupied by tetrominos and what spaces are empty.

## Installation
- Clone the repository
- This project uses elixir 1.15.5-otp-26 as specified in the `.tool-versions` file. You can use asdf to install the correct version of elixir by running `asdf install` in the root of the project.
- Run `mix deps.get` to install the dependencies.
- Run `iex -S mix` to start the application.


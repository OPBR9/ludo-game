# Simplified Ludo Game

This repository contains a small Python project that implements a
simplified, text‑based version of the classic board game Ludo.  The
objective is to move your token around the board and back to your
starting square.  The first player to complete a lap wins.

## Features

* Supports 2–4 human players.
* Each player controls one token.
* Players must roll a 6 to move out of the yard.
* Landing on an opponent captures their token and sends it back to the
  yard.
* Rolling a 6 grants an extra turn.
* The first player to complete one lap around the board wins.

> **Note:** This is a simplified version of Ludo.  It does not include
> the coloured home columns or safe squares found in the physical
> game, nor does it support multiple tokens per player.  The goal is
> to provide a clear, easy‑to‑read example of game logic that can be
> expanded upon.

## Requirements

* Python 3.7 or later.
* No external dependencies are required—only the Python standard
  library.

## Running the game

Clone this repository or download the `ludo_game` directory, then run
the following command in your terminal:

```bash
python ludo.py
```

You will be prompted for the number of players (between 2 and 4) and
their names.  Players take turns rolling a die, and the game prints
the board and token positions after each move.

## Contributing

Feel free to fork this repository and submit pull requests if you
would like to improve the game, fix bugs, or add new features such as
GUI support, multiple tokens per player, AI opponents, or home
columns.  Contributions are welcome!

## License

This project is licensed under the MIT License.  See the
[`LICENSE`](LICENSE) file for details.
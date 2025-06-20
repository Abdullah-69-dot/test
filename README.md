# US States Map Game

This Python project displays a blank map of the United States. When the user types the correct name of a US state, the program writes the state’s name on its correct location on the map.

## Features

- Blank US map as the starting point
- User is prompted to guess the name of a US state
- If the guess is correct, the state name is displayed on the map at the correct location
- Can be used as an educational game to learn US state names and geography

## How It Works

1. The program opens a window displaying an empty map of the USA.
2. The user types the name of a state.
3. If the name is correct and not already guessed, the state’s name appears at its correct position on the map.
4. The game continues until all states are guessed or the user exits.

## Technologies Used

- Python 3
- Turtle graphics module
- CSV file containing US state names and coordinates

## How to Use

1. Install Python 3.
2. Make sure you have the `turtle` module (comes with standard Python) and a CSV file with state data (usually named `50_states.csv`).
3. Run the script:
    ```bash
    python main.py
    ```
4. Enter your guesses in the prompt window.

## Example

- The map starts blank.
- If you type `Texas` correctly, "Texas" appears on the map at Texas’s location.

## License

Open source under the MIT License.

![Game Screenshot]("https://raw.githubusercontent.com/frank-quoc/Alien-Invasion/master/images/game_sample.png")


# Alien Invasion Game

Alien Invasion is a classic arcade-style game built using Python and Pygame. The objective of the game is to shoot down the aliens before they reach the bottom of the screen.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Game Controls](#game-controls)
- [Project Structure](#project-structure)
- [License](#license)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/alien_invasion.git
    ```
2. Navigate to the project directory:
    ```sh
    cd alien_invasion
    ```
3. Create a virtual environment:
    ```sh
    python -m venv .venv
    ```
4. Activate the virtual environment:
    - On Windows:
        ```sh
        .venv\Scripts\activate
        ```
    - On macOS and Linux:
        ```sh
        source .venv/bin/activate
        ```
5. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

To start the game, run the following command:
```sh
python AlienInvasion.py

Workspace
Collecting workspace information

Here is the README.md file with the provided information:

Game Controls
  Right Arrow Key: Move the ship to the right
  Left Arrow Key: Move the ship to the left
  Spacebar: Fire a bullet
  Q Key: Quit the game
  Mouse Click: Click the "Play" button to start a new game

Project Structure

  alien_invasion/
      ├── __pycache__/
      ├── .gitignore
      ├── alien.py
      ├── AlienInvasion.py
      ├── bullet.py
      ├── button.py
      ├── game_stats.py
      ├── images/
      │   ├── alien.bmp
      │   └── ship.bmp
      ├── scoreboard.py
      ├── settings.py
      └── ship.py


alien.py: Contains the Alien class to represent a single alien.
AlienInvasion.py: The main game file that initializes and runs the game.
bullet.py: Contains the Bullet class to manage bullets fired from the ship.
button.py: Contains the Button class to create and manage buttons.
game_stats.py: Contains the GameStats class to track game statistics.
scoreboard.py: Contains the Scoreboard class to display scoring information.
settings.py: Contains the Settings class to store all game settings.
ship.py: Contains the Ship class to manage the player's ship.

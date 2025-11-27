# Python Aim Trainer

A simple aim training game built with Pygame where targets appear on the screen and the player must click them before they disappear. The game tracks your speed, hits, misses, and accuracy to help you practice mouse precision and reaction time.

## Features

- Growing/shrinking circular targets that you must hit with the mouse.
- Lives system: miss too many targets and the game ends.
- Top status bar showing:
  - Elapsed time
  - Hits
  - Remaining lives
  - Targets per second (speed)
- End screen with:
  - Total time
  - Hits
  - Targets per second
  - Accuracy percentage

## How to Play

1. Run the game script.
2. Targets will appear randomly on the screen.
3. Click on the targets before they shrink away.
4. Each missed target reduces your lives.
5. When you run out of lives, the end screen shows your stats.

## Installation

1. Make sure you have Python 3 installed.
2. Install Pygame:
pip install pygame
3. Save the script as `aim_trainer.py` (or similar) in your project folder.

## Usage

From the project directory, run:

python aim_trainer.py

Use your mouse to click on the targets as they appear.

## Skills Learned and Used

- Python game development with Pygame.
- Working with the game loop (`while` loop with `clock.tick()`).
- Handling user input (mouse clicks and quit events).
- Basic collision detection using distance formula.
- Drawing shapes and UI elements (circles, rectangles, text).
- Using timers and events (`pygame.USEREVENT`) to spawn objects.
- Tracking and displaying game statistics (time, hits, misses, accuracy).

## Future Improvements (Ideas)

- Add difficulty levels (faster targets, smaller size).
- Sound effects for hits and misses.
- Main menu and restart option from the end screen.
- High score or best accuracy tracking.

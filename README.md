# Color Rush

A fast-paced browser reaction game where colored blocks fall from the top of the screen and the player matches them by pressing the correct keyboard key before they reach the danger line.

## Gameplay

- Colored blocks fall continuously at increasing speed.
- Each block is tied to one key:
  - A = Red
  - S = Blue
  - D = Green
  - F = Yellow
- Press the matching key before the block reaches the bottom to score points.
- Missing too many blocks ends the run.
- Consecutive correct hits build a combo, increasing your score.

## Objective

Survive as long as possible, keep your streak alive, and maximize your score before you hit the miss limit.

## Controls

- A: Red
- S: Blue
- D: Green
- F: Yellow
- R: Restart after game over
- Any key: Start the game from the title screen

## Game Rules

- Each successful hit adds points.
- Combo bonuses reward streaks of correct inputs.
- Wrong key presses reduce score.
- Missing a falling block also reduces your score and counts toward your misses.
- The game ends when the player reaches the miss limit.

## Files

- `color_rush.html` — complete game implementation in a single HTML file

## How to Run

1. Open `color_rush.html` in a web browser.
2. Press any key to begin.
3. Use the color keys to clear falling blocks.

## Notes

This project is a lightweight HTML5 canvas game with built-in sound effects and a local high-score save using browser storage.

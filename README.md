# Fox Math Meadow

A visually rich, browser-based Three.js math game for early elementary learners. Players guide **Fia the fox** through a colorful 3D meadow, choose the correct answer lane, collect stars, and practice age-appropriate math in a playful, low-pressure way.

![Game type](https://img.shields.io/badge/Game-Three.js%20Browser%20Game-orange)
![Audience](https://img.shields.io/badge/Audience-1st%20Grade%20Math-yellow)
![File type](https://img.shields.io/badge/Format-Single%20HTML%20File-blue)

## Overview

**Fox Math Meadow** is designed for a 1st grade student in the United States. The game combines simple math practice with an engaging 3D runner-style experience. The player moves Fia between answer lanes, selects the correct answer, earns stars, and receives friendly visual feedback.

The game also includes a special **Stop Challenge**. Pressing the space bar opens a kindergarten-level math question. If the player answers correctly, Fia safely stops for a few seconds and celebrates. If the player answers incorrectly, Fia pauses and shakes her head before continuing.

## Play the Game

If hosted with GitHub Pages, the game can be played at:

```text
https://YOUR-GITHUB-USERNAME.github.io/fox-math-meadow/
```

Replace `YOUR-GITHUB-USERNAME` with your GitHub username.

## Local Setup

This game is contained in a single HTML file.

### Option 1: Open Directly

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Make sure you have an internet connection because Three.js is loaded from a CDN.

### Option 2: Run with a Local Server

Some browsers behave better when games are served from a local web server.

From the project folder, run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## File Structure

```text
fox-math-meadow/
├── index.html
└── README.md
```

The entire game is inside `index.html`, including:

- HTML structure
- CSS styling
- JavaScript game logic
- Three.js scene setup
- Fox character construction
- Math problem generation
- Game state management
- Keyboard and touch controls

## Controls

### Keyboard

| Key | Action |
|---|---|
| Left Arrow / A | Move left |
| Right Arrow / D | Move right |
| Up Arrow | Speed up while held |
| Space | Open Stop Challenge |
| Enter | Start or restart game |

### Touch Controls

On mobile or tablet, use the on-screen buttons:

| Button | Action |
|---|---|
| Left | Move left |
| Right | Move right |
| Speed | Speed up while held |
| Stop | Open Stop Challenge |

## Gameplay

The goal is to help Fia collect stars by choosing the correct math answer lane.

1. A math problem appears on screen.
2. Three mushroom answer gates appear in the meadow.
3. Move Fia into the lane with the correct answer.
4. Correct answers earn stars and points.
5. Incorrect answers cost a heart.
6. Collect all stars to win.

## Math Skills Practiced

The main game focuses on 1st-grade-friendly math, including:

- Addition up to 20
- Subtraction up to 20
- Missing-number addition problems
- Number sense
- Quick answer recognition

The Stop Challenge uses easier kindergarten-level math, including:

- Counting stars
- Addition up to 5
- Subtraction up to 6

## Game Features

- Cute low-poly fox character named Fia
- Animated fox legs while moving forward
- Speed boost when holding Up Arrow or the Speed button
- Kindergarten-level Stop Challenge using the space bar
- Celebration hop and flip when a problem is answered correctly
- Head shake and short pause when a problem is answered incorrectly
- Colorful Three.js meadow environment
- Answer mushrooms that disappear before reaction animations
- Score, hearts, star goal, and streak tracking
- Game over and win screens
- Restart support
- Keyboard and touch-friendly controls
- Responsive layout for desktop and mobile screens

## Educational Design Notes

This game is designed to feel encouraging rather than punitive.

- Problems are short and visually clear.
- There are only three answer choices at a time.
- Correct answers trigger celebration animations.
- Incorrect answers give feedback and allow the player to continue.
- The Stop Challenge gives younger learners an easier moment of success.
- The speed boost adds excitement without changing the core learning goal.

## Recommended Age Range

Best for:

- Kindergarten students who are ready for early addition and subtraction
- 1st grade students practicing addition and subtraction fluency
- Younger students who benefit from visual and game-based learning

## Customization Ideas

You can modify `index.html` to adjust the game.

### Make the game easier

Look for the math problem generation functions and reduce the number ranges.

Ideas:

- Use only addition up to 10
- Remove missing-number problems
- Increase the number of lives
- Lower the number of stars needed to win

### Make the game harder

Ideas:

- Add addition up to 30
- Add subtraction with larger numbers
- Add time-based scoring
- Add more answer lanes
- Increase the speed over time

### Change the theme

Ideas:

- Winter fox trail
- Forest treasure hunt
- Space fox adventure
- Farm animal math race
- Ocean animal number quest

## Hosting on GitHub Pages

To publish the game online:

1. Rename the game file to `index.html`.
2. Commit `index.html` and `README.md` to a GitHub repository.
3. Open the repository on GitHub.
4. Go to **Settings**.
5. Go to **Pages**.
6. Set the source to deploy from the `main` branch and `/root` folder.
7. Save the settings.
8. Open the GitHub Pages URL once deployment finishes.

The final URL usually looks like:

```text
https://YOUR-GITHUB-USERNAME.github.io/fox-math-meadow/
```

## Development Notes

This game uses:

- HTML
- CSS
- JavaScript
- Three.js

No build system is required.

Because Three.js is loaded from a CDN, the game needs internet access unless you replace the CDN script with a local Three.js file.

## License

This project is intended for personal, educational, and family use. Add a formal license file if you plan to share, remix, or publish it more broadly.

## Credits

Created as a playful educational math game concept featuring Fia the fox.

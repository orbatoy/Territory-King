# Territory King

A land grab game for one player. Steer a coloured dot, loop back home to claim land and beat the rival players.

Made by [AST Digital](https://astdigital.com.au/). Free for education and non-commercial use. See [LICENSE.md](LICENSE.md).

## What it is

You drag a finger to steer. You leave your land, draw a trail, and loop back home. Everything inside the loop becomes yours. Rivals do the same. If anything touches a trail, the owner of that trail is out. You can cut a rival's trail to knock them out.

## How to play

1. Open `territory-king.html` in a web browser. There is nothing to install.
2. Tap Play.
3. Drag a finger anywhere on the screen to steer in any direction. On a keyboard, use the left and right arrow keys, or A and D.
4. Leave your land and loop back to claim the area inside your trail.
5. Press Space or P to pause.

Touching the edge of the arena is safe. You just slide along it. Turning back over your own trail ends the round.

## Levels

| Level | Arena | Rivals |
|---|---|---|
| Easy | Small rectangle | 3 |
| Medium | Large circle | 15 |
| Hard | Giant hexagon, 5 times bigger than Medium | 25 |

Each level keeps its own saved game and best percentage.

## Bonuses

Three bonuses appear in each game, one every 30 seconds. Each one appears just off screen, and an arrow points to it. Touch it or enclose it in your land to collect it. Each bonus lasts 10 seconds.

- **Anvil:** your land turns into a metal checker plate and you cannot be knocked out. Rivals that hit you are knocked out instead.
- **Eye:** the view zooms out a little so you can see more of the arena.
- **Lightning:** you move 40% faster.

## Other features

- A gold crown shows who holds the most land.
- A slow replay shows where a rival cut your trail.
- Each round gives you a new bright colour and pattern.
- A picture of your captured land shows on the game over screen.
- Dark mode and light mode. The game starts in dark mode.
- A how to play screen with animated pictures and a bonus page.

## Saving

The game saves your progress and best percentage for each level in your browser (localStorage) every 3 seconds. When you open the game again it loads your saved game and shows a Resume button.

## Technical details

- One HTML file with the CSS and JavaScript inside.
- Works offline.
- Made for an 890 x 530 screen. The game scales to fit.
- No libraries or frameworks.
- No online links.
- Uses fonts already on the device. No web fonts.

## Licence

Free for education and non-commercial use only. You may not sell it or use it for commercial purposes. For a commercial licence, contact AST Digital through [astdigital.com.au](https://astdigital.com.au/).

Read the full terms in [LICENSE.md](LICENSE.md).

## AI disclaimer

Development with the assistance of AI. Mistakes can occur.

## About AST Digital

[AST Digital](https://astdigital.com.au/)

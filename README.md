# Racing Game

A small racing game written in C as a group project for our Programming and IT Fundamentals course.

The idea is simple: race against the computer on a randomly generated track and try to reach the finish line first. Each turn, you roll a dice to determine how far your car moves. Some tiles have special effects that can either help you get ahead or slow you down.

## How It Works

- The track gets a random length between 10 and 55 tiles.
- You play against the computer.
- Each side has two cars.
- A dice roll determines how many tiles a car moves.
- Dice values range from -5 to +5.
- Special tiles can move cars forward or backward.

## Special Tiles

| Tile | Effect |
|:---:|---|
| +1 | Move forward 1 tile |
| +3 | Move forward 3 tiles |
| +5 | Move forward 5 tiles |
| -1 | Move backward 1 tile |
| -3 | Move backward 3 tiles |
| -5 | Move backward 5 tiles |

## Built With

- C
- Standard C Library

## Team

**K4 Group**

- **Arvydas Brandišauskas** – Game logic, track generation, dice mechanics and car movement.
- **Nedas Gražinskas** – Game visualization, controls and displaying game progress.

Both of us are responsible for combining the code and testing the final game.

## Development Progress

- [x] Basic racing mechanics
- [x] Random track length
- [x] Dice rolls
- [ ] Two cars for each player
- [ ] Special track tiles
- [ ] Improved computer logic
- [ ] Final testing and bug fixes

## About

This is our university group project, developed as part of the Programming and IT Fundamentals course (November 2026).

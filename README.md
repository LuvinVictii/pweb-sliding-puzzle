
# Sliding-puzzle

A sliding puzzle, also known as a sliding block puzzle or sliding tile puzzle, is a type of puzzle game that involves rearranging a set of square tiles (or sometimes rectangular tiles) within a grid to form a specific pattern, image, or solution. The tiles are usually numbered or contain parts of an image, and there is typically one empty space within the grid to allow movement.

The most common form of sliding puzzle is the 15-puzzle, which consists of a 4x4 grid with 15 numbered tiles and one blank space. The goal is to arrange the tiles in numerical order, with the empty space typically located in the bottom-right corner. To achieve this, you must slide the tiles horizontally or vertically to create a sequence from 1 to 15.

Sliding puzzles can vary in complexity and grid size. They can also feature various images, patterns, or challenges, making them popular as brain teasers and recreational games. Some sliding puzzles are designed to be solved quickly, while others can be quite challenging and require a series of precise moves to solve.

The sliding puzzle I made was the 9-puzzle variety, which features a 3x3 grid with 8 tiles, each numbered between 1 and 8. The goal is the same as the 15-puzzle: to arrange the tiles in numerical order. If the tiles are in the wrong position, they will be colored grey. But if they are in the right position, they will turn cyan.

![image](https://github.com/LuvinVictii/pweb-sliding-puzzle/assets/78089862/79c138da-1c36-4e02-95ed-92d8434fc524)

### Implementation in vanilla JS and CSS.

## Features
* Shuffle function that performs 20 valid random moves.
* Solve function that (naively) solves the puzzle. To be improved!
* Mobile-friendly
  * CSS `translateXY()` animations for mobile performance
  * Optimized for both smaller and larger screen sizes
* Pure vanilla Javascript. No external libraries used. 

## Game flows
### 1. Play
When players open the game, they will see a solved puzzle with all of the tiles colored cyan. To start playing, players can click the "Shuffle" button to shuffle the puzzle.

### 2. Solve the Puzzle
Players can click a valid tile on the right/left/top/bottom of the empty space. This action will slide the clicked tile into the empty space so that the original position of the tile becomes the empty space.

### 3. Stuck?
If a player feels stuck in the current tile position, they can click the "Solve" button to automatically solve the puzzle. This allows them to restart the game by clicking the "Shuffle" button again.

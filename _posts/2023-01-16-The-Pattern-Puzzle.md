---
layout: post
title:  "The Pattern Puzzle"
date:   2023-01-16 18:00:28 -0800
categories: research
---

## [Pattern](https://www.chiark.greenend.org.uk/~sgtatham/puzzles/js/pattern.html)

---

### Objective

In the grid of squares, all must be filled in either black or white. On the sides of the grid, there are numbers, and the value of them must match the length of consecutive black squares.

For example, in figure 1 the numbers in the 3rd row are 5 and 1. Therefore, in that row there are 5 consecutive black squares and 1 black square. Additionally, the squares are also in the same order as the numbers, 5 squares followed by 1 square from left to right.

![figure 1](https://res.cloudinary.com/dfyhppahy/image/upload/v1673922238/Screen_Shot_2023-01-16_at_6.23.15_PM_hxqd78.png)
*Figure 1*

---

## How to Play

You use your mouse to click the squares. Left click makes the square black; right makes it white. To make the square gray again, you can use the middle mouse button, or shift-click the square. Click and drag to mark several squares at once.

### Errors

If you have the wrong amount of black squares than the correct amount in the row (Figure 2), or the numbers don't correspond to the squares correctly (Figure 3), the numbers on the sides will change to red. However, the numbers only change colors when all the squares are filled in.

![figure 2](https://res.cloudinary.com/dfyhppahy/image/upload/v1674015416/Screen_Shot_2023-01-17_at_8.15.54_PM_kltkvz.png)
*Figure 2*

![figure 3](https://res.cloudinary.com/dfyhppahy/image/upload/v1674015415/Screen_Shot_2023-01-17_at_8.10.13_PM_dunut5.png)
*Figure 3*

However, the game does not tell you whether you correctly put the squares, adding to the difficulty

### Options

On the top of the screen there are 7 buttons,

![7 buttons](https://res.cloudinary.com/dfyhppahy/image/upload/v1674017753/Screen_Shot_2023-01-17_at_8.55.48_PM_jrmq8e.png)

- Game: Allows the player to enter Game ID (changes the numbers and grid size), Game random seed, and download and upload a save file.
- Type: You can change the grid size to presets (10x10, 15x15, 20x20, 25x25, 30x30) or enter your custom grid.
- New game: Spawns a new random grid.
- Restart game: Resets all progress.
- Undo move: Cancels your most recent move.
- Redo move: Re-does a canceled move.
- Solve game: Displays the completed grid.

---

## Completion

Upon completion of the game, the grid flashes, indicating that you have solved it correctly.

![Figure 4](https://res.cloudinary.com/dfyhppahy/image/upload/v1674017252/Screen_Shot_2023-01-17_at_8.47.19_PM_r8wgkr.png)
*Figure 4*

## Strategies

As simple as this game might seem at first, personally I found it to be quite difficult. I struggled to even get started on the grid without messing up somewhere. The default grid is 15 by 15, but I decided to start with the 10 by 10. Here I finished the game for the first time and I started to develop a strategy

Look at the top, bottom, rightmost and leftmost rows and columns. Out of these 4, find the section that has the highest value when the numbers are added.

After you find the row, you know that if the outside row has a black square, there has to be a consecutive black square next to it. Example shown in figure 5  

![figure 5](https://res.cloudinary.com/dfyhppahy/image/upload/v1674016841/Screen_Shot_2023-01-17_at_8.40.33_PM_n2ajxd.png)
*Figure 5*

From here, it's just using logic to figure out where the rest goes!

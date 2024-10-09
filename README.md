# Moving Balls Program

## Overview

The Moving Balls program is a simple web-based animation that displays colorful balls bouncing around the browser window. Each ball moves independently, changing direction upon hitting the window edges. This interactive program is a great way to explore basic concepts of JavaScript, including DOM manipulation, randomization, and animation.

## Features

- **Colorful Balls**: Each ball is assigned a random color from a predefined palette.
- **Dynamic Movement**: Balls move across the screen, bouncing off the edges.
- **Randomized Position and Velocity**: Each ball starts at a random position with a random velocity.

## Technologies Used

- HTML
- JavaScript (ES6)

## How to Use

1. **Open the HTML File**: Save the code to an `.html` file (e.g., `moving_balls.html`) and open it in a web browser.
2. **Watch the Animation**: Five colorful balls will be displayed and will move around the screen, bouncing off the edges.

## Code Explanation

- **Ball Creation**: The `create()` function generates a ball with random properties (color, position, and velocity) and appends it to the document body.
- **Randomization Functions**: 
  - `randomColor()` selects a color from a predefined palette.
  - `randomx()` and `randomy()` generate random coordinates within the window dimensions.
  - `randomVelocity()` produces a random velocity for movement.
- **Movement Logic**: The `moveBalls()` function updates the position of each ball based on its velocity. It checks for collisions with the window edges to reverse direction if necessary.
- **Animation Loop**: `setInterval(moveBalls, 10)` calls the `moveBalls()` function every 10 milliseconds to create a smooth animation effect.

## Customization

You can easily customize the following aspects of the program:

- **Number of Balls**: Change the value in the for loop that initializes the `ball` array.
- **Ball Size**: Modify the `height` and `width` properties in the `create()` function.
- **Color Palette**: Add or remove colors in the `palet` array within the `randomColor()` function.

## Conclusion

This Moving Balls program serves as a fun introduction to JavaScript animations and can be expanded or modified for further learning and experimentation. Enjoy playing around with the code!

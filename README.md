# MAGD-150
Github project for MAGD-150 Spring 2023 course created by _Jordan Heath_.
## Project 6 (Located in repository as Heath-6.zip)
This project is a recreation of the retro game character, Pac-Man, using the p5.js library. The character is created using yellow arc shapes, and follows the mouse cursor around the canvas. The background is set to black, and randomly moving white dots are drawn on the canvas to simulate the dots Pac-Man would eat in the game.
### Getting started
To run the project, simply open the **index.html** file in a web browser that supports the p5.js library. No additional installations or configurations are necessary.
### How to use
Move your mouse cursor around the canvas to move Pac-Man. The white dots will move randomly around the canvas, and Pac-Man can "eat" them by passing over them.
### Code Description
The **setup()** function initializes the canvas and sets up the arrays used to track the position of the white dots and Pac-Man.

The **draw()** function is responsible for drawing the white dots and Pac-Man on the canvas.

The **white_dots** array holds objects with x and y properties, which are used to randomly position the white dots on the canvas. These objects are updated on each frame by adding a random value to their x and y properties, and then ensuring that they remain within the bounds of the canvas.

The **x_pos** and **y_pos** arrays hold the position of Pac-Man on the canvas, and are updated on each frame to follow the position of the mouse cursor.

## Project 7 (Located in repository as Heath-7.zip)
This project displays clouds and temperature on a canvas using the p5.js library. The clouds are created using the **makeClouds()** function, which takes in cloudX and cloudY parameters to specify the location of the clouds on the canvas. The temperature is calculated using the **calculateCelcius()** function.
### Getting started
To run the project, simply open the **index.html** file in a web browser that supports the p5.js library. No additional installations or configurations are necessary.
### How to use
The project is a visual representation of clouds and temperature. The clouds are drawn on the canvas using the **makeClouds()** function, which creates a set of three white ellipses to resemble a cloud. The temperature is set using the **farenheitTemp** variable, and is displayed in Celsius using the **calculateCelcius()** function.
### Code Description
The **setup()** function initializes the canvas and sets up the color and angle modes used in the project. The **celciusTemp** variable is calculated using the **calculateCelcius()** function and printed to the console.

The **makeClouds()** function creates a set of three white ellipses to resemble a cloud. The **draw()** function uses the **scale()** method to update the drawing, and creates multiple clouds using a for loop.

The temperature is displayed using ellipses in the **draw()** function. The **calculateCelcius()** function takes in a Fahrenheit temperature and returns the equivalent temperature in Celsius.

## Project 8 (Located in repository as Heath-8.zip)
This program displays three images, a dog, a cat, and a frog, on a canvas. The user can move the dog and the frog images by moving the mouse over the canvas. The cat image remains fixed in the center of the canvas.
### Getting started
1. Load the program onto a web server that can run p5.js scripts.
2. Open the HTML file in a web browser.
3. The program will display the three images on a canvas.
4. Move the mouse over the canvas to move the dog and frog images.
#### Additional notes
- The program uses **loadImage()** to preload the three images before displaying them on the canvas.
- The program uses **text()** to display the word "Hello!" in the center of the canvas.
- The program uses **textFont(), stroke(), fill(), textSize(), and textAlign()** to style the text.
- The program uses **image()** to display the three images on the canvas.
- The position of the dog and frog images is determined by the position of the mouse using the mouseX and mouseY variables.

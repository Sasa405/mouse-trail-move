# mouse-trail-move

Mouse Trail Animation

This project is a simple JavaScript animation that creates a mouse trail effect on a canvas.
As the user moves the mouse, colorful particles follow the cursor, leaving a trail behind. 
The animation continuously updates and renders the particles on the canvas.


The code creates a mouse trail animation on a canvas element. Here's a summary of its functionality:

- The script retrieves the canvas element and its 2D rendering context.

- The canvas dimensions are set to match the window's inner dimensions.

- Two variables, `spots` and `hue`, are initialized.

- An object, `mouse`, is created to store the current mouse position.

- An event listener is added to the canvas, tracking the mouse movement. When the mouse moves, 
  three new instances of the `Particle` class are created and added to the `spots` array.

- The `Particle` class represents a particle in the animation. It initializes the particle's position, size, 
  speed, and color based on the mouse position and a hue value.

- The `update` method of the `Particle` class updates the particle's position and decreases its size over time.

- The `draw` method of the `Particle` class renders the particle as a filled arc on the canvas.

- The `handleParticles` function updates and draws all particles, as well as draws lines between particles 
  that are close to each other.

- The `animate` function clears the canvas, handles the particles, increments the hue value, 
  and requests the next animation    frame.

- Event listeners are added for the window's resize and mouseout events to update the canvas dimensions and 
  reset the mouse position, respectively.

- Finally, the `animate` function is called to start the animation loop.

This code can be used to create an interactive and visually appealing mouse trail effect on a webpage.



# Dependencies

This project has no external dependencies. 

It is built using plain HTML, CSS, and JavaScript.




# Acknowledgments

This project was inspired by various mouse trail animations and aims 
to provide a simple implementation for educational purposes.


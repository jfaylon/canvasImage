# canvasImage

# Thought process
1. I started with trying to upload an image and put it on the canvas.
2. Tried to resize/scale/align to center of the canvas
3. Find a way to save the image and its coordinates by using JSON objects
4. Then experimented on how to create a rectangle based on various coordinates with the use of mouse events and variables
5. Check out the mouse events to trigger the input field while inside the circle
6. Find a way to save the values in the local storage and trigger the events to refresh the data
7. Use buttons to traverse to the different photos using events
8. For the gallery, resize the images to be a thumbnail and use of events to trigger the traversal and access of the data.


# Known Issues
- dragging text collison
- dragging the rectangle from lower right to upper left causes the input field to be out of the box

# Limitations
- Only for modern browsers (Tested on Chrome)
- Fixed text font and color
- Resized images based on canvas resolution
- Has not been fully tested yet on mobile phones with varying resoltions and browsers

# Rooms for Improvement
- Choice of options for text and border colors
- CSS Styling
- Collision detection needs improvement
- Move the javascript files out and refactor for modules
- Move CSS to a separate file.
- Make the code cleaner by using convenience methods (JQuery, lodash, etc.)
- Reduce repetitive code by using functions

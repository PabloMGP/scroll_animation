# scroll_animation
This simple app demonstrates a minimalist scroll animation that triggers the appearance of elements as the user scrolls down the page. The animation adds a subtle touch of interactivity to your web content, making it more engaging for visitors.

## Features
Scroll Animation: As the user scrolls down the page, elements with the .box class come into view with a smooth fade-in animation.

## How It Works
When the user scrolls, the checkBoxes function is called. This function calculates a trigger point based on the window's height, and then checks the position of each element with the .box class. If an element's top position crosses the trigger point, it receives the .show class, triggering the animation.

The script utilizes the getBoundingClientRect() method to determine the element's position relative to the viewport. As the user scrolls, the scroll event listener constantly monitors the elements' positions and updates the animation accordingly.

## Usage
Open the index.html file in your web browser and scroll down the page to witness the scroll animation in action.

## Customization
Feel free to use this code in your own applications. Adjust the trigger point and animation style by modifying the checkBoxes function in the script.js file.


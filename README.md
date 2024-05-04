# drumkit
This drum kit project is a simple web application that allows users to play different drum sounds by either clicking on buttons displayed on the webpage or by pressing corresponding keys on their keyboard.

HTML Structure:
The HTML file (index.html) defines the structure of the webpage. It includes:

A heading (<h1>) with the title "Drum 🥁 Kit".
Seven buttons, each representing a different drum sound. Each button has a class of "drum" and a unique letter (w, a, s, d, j, k, l) representing the key associated with the drum sound.
An external JavaScript file (index.js) that provides functionality to the buttons.
A footer section displaying the creator's name.
CSS Styling:
The CSS file (styles.css) provides styles to make the webpage visually appealing. It includes styling for:

Background color and text alignment.
Heading and footer.
Drum buttons, including background images and visual effects when clicked.
A special styling for the "pressed" class to create an animation effect when a button is clicked.
JavaScript Functionality:
The JavaScript file (index.js) adds interactivity to the webpage. It:

Selects all elements with the class "drum" and adds click event listeners to them.
Plays the corresponding drum sound when a button is clicked or a key is pressed.
Triggers a visual animation effect on the button that is clicked or the key that is pressed.
Determines which drum sound to play based on the key or button clicked using a switch statement.
Defines a makeSound() function to play the appropriate sound.
Defines a buttonAnimation() function to create a visual animation effect on the active button.
How It Works:
Open the HTML file (index.html) in a web browser.
Click on the drum buttons displayed on the webpage or press the corresponding keys (w, a, s, d, j, k, l) on your keyboard.
Each button click or keypress triggers the associated drum sound and visual animation effect.
Enjoy playing different drum sounds and creating beats!
Conclusion:
This project provides a fun and interactive way for users to experiment with drum sounds and create simple rhythms. It demonstrates how HTML, CSS, and JavaScript can be combined to create dynamic and engaging web applications.

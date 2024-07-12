# randomBackgroundColorChanger
The fourth project under the FCC JS algorithms and data structures curriculum.
This project is a simple web application that changes the background color of the page to a random dark color from a predefined list when a button is clicked. 
The current background color's hex code is also displayed on the page.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Code Explanation](#code-explanation)

## Overview
This application provides a fun and interactive way to change the background color of a webpage. 
It utilizes a predefined array of dark color hex codes and randomly selects a color from this array whenever the user clicks a button.

## Features
- Changes the background color to a random dark color on button click.
- Displays the current background color's hex code on the page.

## Getting Started
Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites
- A web browser (e.g., Chrome, Firefox, Edge, etc.)

### Installation
1. Clone the repository
2. Navigate to the project directory
3. Open the index.html file in your web browser

## Usage
1. Open the index.html file in your web browser.
2. Click the "Change Background Color" button.
3. Observe the background color change and the corresponding hex code displayed on the page.

## Code Explanation
The core functionality is implemented in JavaScript. Here’s a brief explanation of the main parts of the code:

### HTML
The HTML file contains a button and a span element to display the hex code of the current background color.

### JavaScript
#### Variables
- btn: Selects the button element.
- body: Selects the body element.
- bgHexCodeSpanElement: Selects the span element to display the hex code.
- darkColorsArr: An array of predefined dark color hex codes.

#### Functions
- getRandomIndex(): Generates a random index to select a color from darkColorsArr.
- changeBackgroundColor(): Changes the background color to a randomly selected color from darkColorsArr and updates the span element with the new color's hex code.

#### Event Listener
- btn.onclick: Sets up an event listener on the button to call changeBackgroundColor() when the button is clicked.

# User Interaction Message Update

This is a simple web example demonstrating how to update a message on a webpage after user interaction. The example uses an external script to listen for user events (like keyboard, mouse, and touch events) and update the message displayed on the page once the user interacts.

## Features
- Displays an initial message ("Waiting for user interaction...").
- Upon user interaction, the message is updated to "Hello from external script!".
- The interaction logic is handled by an external JavaScript file (`externalScript.js`).
  
## How It Works

1. The HTML file contains the structure of the page, including the message element.
2. The external script listens for specific user events (`keydown`, `mouseover`, `touchmove`, etc.).
3. Once the user interacts, the message displayed on the page is updated via the external script.

## Files

- `index.html`: The main HTML file that contains the structure and loads the external script.
- `externalScript.js`: An external JavaScript file that listens for user interaction events and updates the message on the page.

## Installation

You can clone this repository and run the `index.html` file directly in your browser.

``` 
git clone https://github.com/indrajithc/user-interaction-message-update.git
cd user-interaction-message-update
npm i
npm start
``` 

## License

This project is open-source and available under the [MIT License](LICENSE).

# Modal Window Project

This project demonstrates a simple modal window with HTML, CSS, and JavaScript. 

## Features

- Open and close a modal window by clicking buttons.
- Close the modal by clicking the overlay or pressing the `Escape` key.
- The modal includes a title, close button, and a text description.

## Files

- `index.html`: The main HTML file containing the structure of the page.
- `css/style.css`: The CSS file to style the modal and overlay elements.
- `js/master.js`: The JavaScript file that manages the modal's functionality.

## How to Use

1. Open `index.html` in a browser to view the project.
2. Click on any **"Show modal"** button to open the modal.
3. Click the close button, the overlay, or press `Escape` to close the modal.

## Example Code

Here is a snippet from `js/master.js` demonstrating the modal control functions:

```javascript
const openModal = function () {
  modal.classList.remove("hidden");
  overlay.classList.remove("hidden");
};

const closeModal = function () {
  modal.classList.add("hidden");
  overlay.classList.add("hidden");
};

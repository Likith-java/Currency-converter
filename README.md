### Currency Converter

This is a simple Currency Converter application built with HTML, CSS, and JavaScript. It allows users to convert a specified amount of one currency to another and displays the corresponding flags for the selected currencies.

#### Project Files

* **`index.html`**: The main structure of the application. It includes the input field for the amount, the dropdown menus for currency selection, the display area for the converted value, and links to the CSS and JavaScript files.
* **`style.css`**: This file provides all the styling for the application. It makes the user interface visually appealing by setting the layout, colors, and fonts for all the elements.
* **`codes.js`**: A JavaScript file that acts as a database. It contains a `countryList` object that maps three-letter currency codes (e.g., USD, INR, EUR) to their corresponding two-letter country codes (e.g., US, IN, FR). This is used by `script.js` to fetch and display the correct country flags.
* **`script.js`**: The core logic of the application. It dynamically populates the currency dropdowns, handles user input, updates the flag images based on the selected currencies, and fetches the exchange rate from an external API to perform the conversion. It also includes logic to prevent invalid inputs by defaulting the amount to "1" if a value less than 1 or no value is entered.

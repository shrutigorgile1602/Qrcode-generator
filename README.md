# QR Code Generator

## Overview
The provided code is a simple web application that allows users to generate QR codes based on the text or URL they input. Users can select the size of the QR code and generate and download the QR code image.

## HTML Structure
1. `<!DOCTYPE html>`: This declaration specifies that the document is an HTML5 document.
2. `<html lang="en">`: The root element of the HTML document. It specifies the document's language as English.
3. `<head>`: Contains meta-information about the document and links to external resources.
   - `<meta charset="UTF-8">`: Sets the character encoding to UTF-8.
   - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Configures the viewport for responsive design.
   - `<title>QR CODE GENERATOR</title>`: Sets the title of the webpage.
   - `<link rel="stylesheet" href="style.css">`: Links an external CSS stylesheet for styling.
4. `<body>`: Contains the visible content of the webpage.
   - `<div class="box">`: A container for the entire QR code generator application.
     - `<div class="qr-header">`: Header section containing the QR code title, text input field, and size selection dropdown.
     - `<div class="qr-body">`: Empty container where the generated QR code will be displayed.
     - `<div class="qr-footer">`: Footer section with buttons for generating and downloading the QR code.
       - `<a href="" id="generateBtn">Generate</a>`: Button for generating the QR code.
       - `<a href="" id="downloadBtn" download="QR_Code.png">Download</a>`: Button for downloading the generated QR code with a specified filename.
   - `<script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>`: External script for generating QR codes using the qrcode.js library.
   - `<script src="script.js"></script>`: Custom JavaScript code to handle user interactions and generate the QR code.

## CSS Styles
The styling for this QR code generator is provided in an external CSS file (`style.css`). The CSS is responsible for the visual presentation of the webpage, including colors, fonts, and layout.

## JavaScript Functionality
The JavaScript code in `script.js` is responsible for implementing the QR code generation functionality. It uses the qrcode.js library to generate QR codes based on user input and selected size.

## Usage
1. Open the HTML file in a web browser.
2. Enter the text or URL you want to encode into a QR code in the input field.
3. Select the desired size for the QR code from the dropdown menu.
4. Click the "Generate" button to create the QR code, which will be displayed in the designated area.
5. Click the "Download" button to save the generated QR code as a PNG image file with the filename "QR_Code.png" to your device.

## Dependencies
- The code uses the qrcode.js library to generate QR codes. Ensure that the library is correctly loaded from the provided CDN link (`https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js`).

## Customization
You can customize the appearance and behavior of the QR code generator by modifying the CSS in `style.css` and the JavaScript in `script.js`. You can also adjust the available QR code sizes by editing the `<select>` element in the HTML code.

## Compatibility
This QR code generator should work on most modern web browsers, including Google Chrome, Mozilla Firefox, Microsoft Edge, and Safari. Make sure you have an internet connection to load external resources (e.g., the qrcode.js library).


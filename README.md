# CAPTCHA Solver

A simple CAPTCHA solver application with a dark theme interface.

## Features

*   Displays a CAPTCHA image (`sample.png` by default).
*   Allows users to input the CAPTCHA text.
*   Verifies the input against a predefined solution for the default image.
*   Supports loading CAPTCHA images from a URL parameter (`?url=`).
*   Provides instant feedback on verification.

## Setup

1.  Clone this repository.
2.  Open `index.html` in your web browser.

## Usage

*   **Default Mode**: The application will display `sample.png`. Enter "ADUR3" to solve it.
*   **Custom Image (Demo only)**: Append `?url=<image_url>` to the browser's URL to load a different image. Note that the verification logic only works for the default `sample.png` in this demo.

## Technologies

*   HTML
*   JavaScript
*   Tailwind CSS

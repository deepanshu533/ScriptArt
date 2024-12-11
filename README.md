

# Handwriting Project

This project is a React application that allows users to create handwriting-style text, change the text dynamically, download the generated image, and use text-to-speech to read the text aloud.

## Features

- **Dynamic Text Input:** Change the text and see it rendered in a handwriting font.
- **Download Image:** Save the generated handwriting image to your local machine.
- **Text-to-Speech:** Listen to the text read aloud using a text-to-speech feature.

## Technologies Used

- **Frontend:** React, CSS
- **Libraries:** 
  - [html2canvas](https://html2canvas.hertzen.com/) for image generation.
  - [ResponsiveVoice](https://responsivevoice.org/) or Web Speech API for text-to-speech.

## Setup and Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/handwriting.git
    cd handwriting-project
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Start the application:**

    ```bash
    npm start
    ```

4. **Open the application:**

    Navigate to `http://localhost:3000` in your browser.

## Usage

1. **Change Text:**
   - Enter your desired text in the input box provided on the web page.
   - The text will be dynamically rendered in a handwriting font.

2. **Download Image:**
   - Click the "Download Image" button to save the rendered text as an image file to your local machine.

3. **Text-to-Speech:**
   - Click the "Speak Text" button to hear the text read aloud.
  


## IMPORTANT NOTES

1. ** Pls downgrade your node version to 17 for smooth expreince **
2. you can do so by installing nvm in windows manualy running following commands

```bash
nvm install 17
```
and switch to version 17 by using command
```bash
nvm use 17
```

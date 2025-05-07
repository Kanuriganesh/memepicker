# Pumpkin's Purrfect Meme Picker 🐱🎃

A fun web app that lets users pick cat memes based on their current emotion, optionally filtered to animated GIFs.

## Features

- Select emotion to filter cat memes
- Option to show only animated GIFs
- Random meme displayed in a modal
- Smooth UI with highlight on selected emotion
- Modular, readable JavaScript structure

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript (ES6 Modules)

## File Structure


## How It Works

1. Emotion options are dynamically rendered from `catsData`.
2. User selects an emotion and optionally checks "GIFs only".
3. Clicking **Get Image** shows a matching random cat meme.
4. Modal displays the image and can be closed with an **X** button.

## Setup

1. Clone the repo
2. Ensure all files including `/images` and `data.js` are in place
3. Open `index.html` in a browser

## Sample `data.js` Structure

```javascript
export const catsData = [
  {
    image: "sleepy-cat.jpg",
    alt: "A sleepy cat",
    emotionTags: ["sleepy", "relaxed"],
    isGif: false
  },
  ...
];

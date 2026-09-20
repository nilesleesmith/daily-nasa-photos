# Daily NASA Photos

A JavaScript application that retrieves NASA's Astronomy Picture of the Day for a date selected by the user.

## About

This project uses NASA's Astronomy Picture of the Day API, commonly called APOD.

The user selects a date, and the application requests NASA's astronomy content for that day.

The returned content may be either an image or a video.

## Features

- Select a date
- Request NASA APOD data
- Display an astronomy image
- Display video content when provided
- Display the content title
- Display NASA's explanation

## How It Works

1. The user selects a date.
2. JavaScript reads the selected value.
3. A request is sent to NASA's APOD API.
4. The response is converted to JSON.
5. The application checks the returned `media_type`.
6. An image or video is displayed.
7. The title and explanation are added to the page.

## What I Practiced

- REST APIs
- `fetch()`
- Promises
- JSON
- Template literals
- Functions
- Conditional statements
- DOM manipulation
- Event listeners
- Date inputs

## Technologies

- HTML5
- CSS3
- JavaScript
- NASA APOD API

## API Key

The current learning version uses NASA's `DEMO_KEY`.

For a larger or production application, a personal NASA API key would normally be preferable because the demo key has lower usage limits.

## Running the Project

1. Clone or download the repository.
2. Open `index.html`.
3. Select a date.
4. Click the button to request the NASA content.
5. View the returned image or video, title, and explanation.

## Purpose

This project was created to practice consuming an external API and displaying different types of API data dynamically in the browser.

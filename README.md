# Stop-watch-By-JavaScript

A simple and elegant stopwatch application built with HTML, CSS, and JavaScript. This stopwatch features start, stop, and reset functionality with a clean and modern user interface.

## Features

- Start: Begin the stopwatch timer
- Stop: Pause the current time
- Reset: Reset the stopwatch to 00:00:00
- Millisecond precision timing
- Clean and responsive design

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)

## Screenshot

![Stopwatch Screenshot](Screenshot%202025-07-23%20085637.png)

## How It Works

The stopwatch displays time in the format `MM : SS : MS` (Minutes : Seconds : Milliseconds).

- The display updates every 10 milliseconds when running
- Time components automatically roll over (100 milliseconds = 1 second, 60 seconds = 1 minute)
- Responsive buttons with distinct colors for different actions:
  - Green: Start button
  - Red: Stop button
  - Blue: Reset button

## Code Structure

- `index.html`: Contains the basic structure and elements of the stopwatch
- `style.css`: Handles all the styling including the dark theme and button colors
- `script.js`: Contains the stopwatch logic and event handlers

## Implementation Details

The stopwatch is implemented using `setInterval()` for timing, with event listeners for button interactions. The time display is updated every 10ms when the stopwatch is running, and the display is formatted to always show two digits for each time component.

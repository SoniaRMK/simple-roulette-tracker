# Roulette Tracker

A lightweight, browser-based European Roulette Tracker built with vanilla HTML, CSS and JavaScript.

Roulette Tracker helps players record roulette outcomes and monitor the frequency and distribution of numbers across different betting categories. Simply enter each winning number (0–36), and the application automatically updates all statistics.

## Features

### Number Frequency
- Tracks all 37 European roulette numbers (0–36).
- Displays the number of times each number has appeared.
- Calculates the percentage frequency of each number.
- Identifies the most and least frequently occurring numbers.
- Shows how many unique numbers have appeared.

### Betting Category Statistics

Automatically categorises recorded results into:

- **Colours:** Red, Black and Green.
- **High / Low:** Low (1–18) and High (19–36).
- **Dozens:** First (1–12), Second (13–24) and Third (25–36).
- **Columns:** First, Second and Third columns.

Each category displays its occurrence count and percentage of total recorded spins.

### Recent Results
- Displays the latest recorded roulette outcomes.
- Uses colour-coded indicators for easy identification.
- Shows the 30 most recent results, with the newest first.

### Session Management
- Automatically saves results using browser `localStorage`.
- Restores previously recorded results when the application is reopened.
- Undo the last recorded result.
- Clear the entire session when needed.

## Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Browser LocalStorage API

No frameworks, external libraries, backend services or database are required.

## Getting Started

### Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/ShewolfTech/roulette-tracker.git
   ```

2. Navigate into the project directory:

   ```bash
   cd roulette-tracker
   ```

3. Open `index.html` in your preferred web browser.

Alternatively, download the repository and open `index.html` directly.

## How to Use

1. Open the application in your browser.
2. Enter the winning roulette number (0–36).
3. Press **Enter** or click **ADD**.
4. The application automatically updates all statistics.
5. Continue recording results as the roulette game progresses.

Use **Undo Last** to remove the most recently entered result or **Clear Session** to reset all recorded data.

## Data Storage

The application uses browser `localStorage` to persist recorded roulette results.

- No user account is required.
- No internet connection is required after loading the application.
- Results remain available when the browser is reopened on the same browser profile.
- Clearing browser site data may permanently erase saved results.
- Data is not automatically synchronised between devices or browsers.

## Roulette Rules

This application follows European roulette rules:

| Category | Numbers |
|---|---|
| Total numbers | 37 (0–36) |
| Red | 18 numbers |
| Black | 18 numbers |
| Green | 0 |
| Low | 1–18 |
| High | 19–36 |
| First dozen | 1–12 |
| Second dozen | 13–24 |
| Third dozen | 25–36 |
| First column | 1, 4, 7 ... 34 |
| Second column | 2, 5, 8 ... 35 |
| Third column | 3, 6, 9 ... 36 |

Zero is excluded from the dozen, column and high/low calculations.

## Important Disclaimer

Roulette outcomes are random, and each spin is independent of previous spins. Historical frequency data does not predict or guarantee future outcomes.

This application is an observation and record-keeping tool, not a betting prediction system.

## Licence

This project is open for personal learning, modification and experimentation. Add a formal licence to the repository if you intend to define permissions for redistribution and reuse.

---

**Built with simplicity by SheWolf Tech.**

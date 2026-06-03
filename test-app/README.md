# Quiz CLI

An interactive command-line quiz game for learning JavaScript and Node.js fundamentals.

## Overview

Quiz CLI is a terminal-based quiz application built with modern JavaScript. It demonstrates core programming concepts including ES modules, async/await, classes, file system operations, and user input handling.

## Features

- Interactive command-line quiz experience
- Multiple quiz categories
- Configurable number of questions per session
- Randomized question order
- Progress tracking with a visual progress bar
- Immediate feedback for each answer
- Final score summary with performance messaging
- Review of incorrect answers at the end of the quiz
- No external dependencies required

## Technologies Used

- Node.js 18+
- ES Modules
- Built-in `readline` module
- Built-in `fs/promises` module
- JSON-based question storage

## Project Structure

- `index.js` - Application entry point
- `src/quiz.js` - Quiz logic and scoring
- `src/input.js` - Input handling utilities
- `src/colors.js` - Terminal color helpers
- `data/questions.json` - Quiz questions and categories
- `package.json` - Project metadata and scripts

## Requirements

- Node.js version 18.0.0 or higher

## Installation

1. Clone the repository.
2. Install dependencies:

```bash
npm install
```

## Running the Application

Start the quiz with:

```bash
npm start
```

## Available Scripts

- `npm start` - Run the quiz application
- `npm test` - Run the test suite

## How It Works

1. Select a quiz category.
2. Choose how many questions to answer.
3. Answer each question from the terminal.
4. Review your score and incorrect answers.
5. Choose whether to play again.

## Learning Highlights

This project is designed to demonstrate:

- ES Modules import/export syntax
- Async/await and Promises
- File reading with Node.js
- Working with arrays and objects
- Classes and object-oriented programming
- Terminal-based user interaction
- Error handling and application flow control

## License

MIT

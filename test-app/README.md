# quiz-cli

An interactive command-line quiz game for learning JavaScript, built with Node.js and designed for a smooth terminal-first experience.

## Project Overview

`quiz-cli` is a lightweight CLI application that presents multiple-choice quiz questions across several categories, tracks your score, and shows a final review of your answers. It uses a structured question bank stored in JSON and provides a polished terminal experience with colored output, progress indicators, and replay support.

## Features

- Interactive command-line quiz gameplay
- Category-based question selection
- Configurable number of questions per round
- Score tracking and progress display
- Final results summary
- Review of incorrect answers with explanations
- Replay option after each quiz session
- ANSI-colored terminal styling for better readability
- Modular codebase with separated input, quiz logic, and styling helpers

## Setup Instructions

### Prerequisites

- Node.js **18.0.0 or newer**
- npm

### Install

1. Clone the repository:
   ```bash
   git clone https://github.com/vignesh-pathi/test-app.git
   ```

2. Navigate to the project directory containing `package.json`:
   ```bash
   cd test-app/test-app
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

### Run the application

Start the quiz game with:

```bash
npm start
```

### Run tests

Execute the test suite with:

```bash
npm test
```

## Usage Examples

### Start a quiz session

```bash
npm start
```

You will be prompted to:

- choose a category
- select the number of questions
- answer each question in the terminal
- review your final score and incorrect answers

### Example quiz flow

```text
Welcome to quiz-cli!
Choose a category: JavaScript Basics
How many questions would you like to answer? 5

Q1. Which keyword declares a block-scoped variable in JavaScript?
1) var
2) let
3) function
4) const

Your answer: 2

Correct! Good job.
```

### Replay the game

After completing a round, you can choose to play again without restarting the application.

## Project Structure

```text
test-app/
└── test-app/
    ├── package.json
    ├── index.js
    ├── data/
    │   └── questions.json
    └── src/
        ├── colors.js
        ├── input.js
        └── quiz.js
```

### Key files

- `index.js` — CLI entry point and main game loop
- `src/quiz.js` — quiz state management and gameplay logic
- `src/input.js` — terminal input helpers built on `readline`
- `src/colors.js` — ANSI color and formatting utilities
- `data/questions.json` — quiz content, categories, and explanations

## Technology Stack

- **Node.js** — runtime environment
- **ES Modules** — modern JavaScript module system
- **Readline** — interactive terminal input
- **JSON** — structured quiz dataset
- **ANSI Escape Codes** — terminal text styling
- **Built-in Node test runner** — test execution via `node --test`

## Contributing

Contributions are welcome. If you'd like to improve the project:

1. Fork the repository
2. Create a feature branch
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes
4. Run tests to verify everything works
   ```bash
   npm test
   ```
5. Commit and push your changes
6. Open a pull request

### Suggested contribution ideas

- Add more quiz questions
- Introduce new categories
- Improve score summaries and progress UI
- Add difficulty levels
- Support timed questions
- Expand automated tests

## License

This project is licensed under the **MIT License**.
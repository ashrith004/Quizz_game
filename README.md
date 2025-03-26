# Quiz Game

A simple True/False quiz game built in Python.

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Features](#features)
- [Example Usage](#example-usage)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)

## Overview
This Python-based quiz game loads questions from a dataset and quizzes the user in a command-line interface. Users respond with `True` or `False`, and their score is updated accordingly.

## Project Structure
```
├── data.py            # Contains the list of questions
├── main.py            # Entry point for running the quiz
├── question_model.py  # Defines the Question class
├── quiz_brain.py      # Manages the quiz logic
```

## How to Run
1. Ensure you have Python installed (>=3.6).
2. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/quiz-game.git
   ```
3. Navigate into the project directory:
   ```sh
   cd quiz-game
   ```
4. Run the script:
   ```sh
   python main.py
   ```

## Features
- Loads a predefined set of True/False questions
- Keeps track of the user’s score
- Simple command-line interface

## Example Usage
```
Q.1: A slug's blood is green. (True/False): True
You got it right!
The correct answer was: True.
Your current score is: 1/1
```

## Future Improvements
- Add multiple-choice questions
- Load questions from an external API or file
- Implement a graphical user interface (GUI)

## Contributing
Feel free to fork this repository and submit pull requests.

## License
This project is open-source and available under the MIT License.


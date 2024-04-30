# Simple Python Quiz GUI using Tkinter

This Python program creates a simple graphical user interface (GUI) quiz application using Tkinter. It's a basic quiz application where users can answer multiple-choice questions and get their results at the end.

## Features

- Simple GUI interface built using Tkinter.
- Questions, options, and answers are loaded from a JSON file.
- Calculates the user's score based on correct answers.
- Displays the result in a message box at the end of the quiz.
- Allows users to navigate through questions and quit the quiz.

## How to Use

1. Make sure you have Python installed on your system.
2. Clone this repository to your local machine.
3. Ensure you have the required JSON data file (`data.json`) with questions, options, and answers.
4. Run the `quiz.py` script using Python.
5. Answer the questions displayed on the GUI interface.
6. Click on the "Next" button to move to the next question or "Quit" to exit the quiz.
7. After answering all questions, the result will be displayed in a message box.

## JSON Data Format

The quiz questions, options, and answers are stored in a JSON file (`data.json`) in the following format:

```json
{
  "question": ["Question 1", "Question 2", ...],
  "options": [["Option 1", "Option 2", "Option 3", "Option 4"], ["Option 1", "Option 2", "Option 3", "Option 4"], ...],
  "answer": [1, 2, ...]
}
```
- `question`: Array of questions.
- `options` : Array of arrays, each containing options for corresponding questions.
- `answer`: Array of integers, where each integer represents the correct option index (starting from 1).

## Dependencies
- Python 3.x
- Tkinter (usually comes pre-installed with Python)
# Python Quiz

This is a simple command-line quiz application built in Python. Users can test their knowledge of Python programming language by answering a series of True/False questions.

## Getting Started

These instructions will help you run the quiz application on your local machine.

### Prerequisites

- Python 3.x

### Installation

1. Clone the repository:
   git clone https://github.com/your-username/Python-Quiz.git
2. Navigate to the project directory

### Running the Quiz

To start the quiz, simply run the following command:
python Main.py

The application will prompt you to enter your name, and then the quiz will begin. You'll be presented with a series of True/False questions about Python. Enter "True" or "False" for each question.

After answering all the questions, the quiz will display your final score.

## Code Structure

The project consists of two Python files:

1. `Main.py`: This file contains the `Quiz` class, which is responsible for running the quiz, displaying questions, and keeping track of the score.
2. `quest.py`: This file contains the `Questions` class, which provides a static method `get_questions()` that returns a list of tuples containing the questions and their respective answers.

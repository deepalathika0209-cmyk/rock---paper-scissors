TITLE : ROCK -PAPER SISSORS

OVERVIEW OF THE PROJECT: ROCK–PAPER–SCISSORS IN PYTHON

The Rock–Paper–Scissors game is a simple hand game played between two players. In this Python project, the player competes against the computer, which makes its choices randomly. The main objective of the game is to create an interactive program that uses conditional statements, random number generation, and user input to simulate the game.

 Project Objective

To build a Python program where:

The user selects Rock, Paper, or Scissors.

The computer randomly selects one option.

The program compares both choices and determines the winner.

 Key Concepts Used

This project helps you uVariables

User input (input())

Random module (random.choice)

If–elif–else conditions

Loops (optional for replaying the game)

Basic game logic

 Working Principle

Import the random module.

Take the user’s choice.

Generate the computer’s choice from the list ["rock", "paper", "scissors"].

Compare both using conditional statements.

Display the result:

Rock beats Scissors
FEATURES OF ROCK–PAPER–SCISSORS IN PYTHON
✅ 1. User vs Computer Gameplay
Scissors beats Paper
2. Random Computer Choice

The computer uses the random module to select rock, paper, or scissors, making the game unpredictable.

 3. Simple and Easy-to-Understand Logic

The game uses basic if–elif–else conditions to compare choices and determine the winner.

 4. Input Validation

The program can be written to check if the user enters a valid option (rock, paper, or scissors).

 5. Automatic Winner Detection

The program automatically applies game rules:

Rock crushes Scissors

Scissors cuts Paper

Paper covers Rock

 6. Replay Option
TECHNOLOGIES / TOOLS USED IN ROCK–PAPER–SCISSORS PYTHON PROJECT
✅ 1. Python Programming Language

The entire project is developed using Python, known for its simplicity and readability.
Used for:

Game logic

User input

Displaying output

 2. Python Standard Library

No external libraries are needed. Only built-in modules.

 3. random Module

Used to generate the computer’s choice randomly using:

random.choice()

 4. Text-based Console / Terminal

The game runs in:

Command Prompt

Terminal

Python IDLE

VS Code Terminal

PyCharm Console

The user interacts through simple text input/output.

 5. Code Editor / IDE (any one)

You can use any development environment such as:

VS Code

PyCharm

Python IDLE

Jupyter Notebook

Thonny

Used for writing and executing the Python script.

 6. Flowchart / Diagram Tools (Optional for Documentation)

If your project includes a flowchart or documentation, tools like:

Draw.io

MS Word

PowerPoint

Google Docs

Notebook diagrams

may be used.

 (Optional if you extend the project)

If you add GUI or advanced features:

Tkinter (for GUI version)

Pygame (for game-like interface)
Step 1: Install Python

Visit the official Python website: python.org

Download the latest Python version for your operating system (Windows/Mac/Linux).
HOW TO INSTALLAND RUN 
Install Python and make sure to check the box “Add Python to PATH” during installation.

 Step 2: Install a Code Editor (Optional but Recommended)

You can write and run the program in:

VS Code

PyCharm

IDLE (comes with Python)

Jupyter Notebook

Thonny

Step 3: Create a New Python File

Open your editor.

Create a new file named:
rock_paper_scissors.py

Copy and paste your Rock–Paper–Scissors code into the file.

 Step 4: Save the File

Save the Python file in a folder where you can easily find it.

Step 5: Run the Project

There are two ways to run the program:

Method A: Using Terminal / Command Prompt

Open Terminal (Linux/Mac) or Command Prompt (Windows).

Navigate to the folder where your file is saved using:

cd folder_path


Run the program:

python rock_paper_scissors.py1. Verify Python Installation

Open the terminal/command prompt.

Run:

python --version


Ensure Python is installed correctly.
3. Test Valid Inputs

Enter each valid input to ensure the program responds correctly:

rock

paper

scissors

Check if:

The computer choice is displayed5. Test All Possible Game Outcomes

Make sure the program correctly handles all scenarios:

User Choice	Computer Choice	Expected Result
Rock	Scissors	User Wins
Scissors	Paper	User Wins
Paper	Rock	User Wins
Scissors	Rock	Computer Wins
Paper	Scissors	Computer Wins
Rock	Paper	Computer Wins
Same Choice	Same Choice	Tie
 6. Test Multiple Rounds

Choose “yes” at replay prompt → ensure game restarts.

Choose “no” → ensure program exits smoothly.

 7. Check Output Formatting

Ensure:

Messages are clear

Choices are shown properly

Results are understandable

 8. Test Performance

Even after multiple rounds, ensure:

No crashing

No slowdowns

Smooth execution

 9. (Optional) Test Scoreboard

If your version has scoring:

Play several rounds

Confirm scores update correctly

The result (win/lose/tie) is accurate

 4. Test Invalid Inputs

Enter invalid entries like:

roc

stone

numbers or symbols

The program should:

Display an error or warning

Ask the user to enter a valid choice

(If your version doesn’t support validation, skip this step.)
 2. Run the Program

Execute the script using:

python rock_paper_scissors.py

Method B: Using Python IDLE
Custom CSS/HTML (for web version
Users can play multiple rounds until they choose to stop.
Paper beats Rocknderstand and apply:

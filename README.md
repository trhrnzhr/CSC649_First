




# CSC649 Python Word and Character Counter

## Description

This program accepts a sentence from the user and calculates the number of words and characters in the input. It also displays a message when the user enters an empty input.

## How to Run

1. Open the project in PyCharm.
2. Make sure the project uses the Python 3.12 virtual environment.
3. Open `main.py`.
4. Click the Run button.
5. Enter a sentence when prompted.

## Features

- Counts the number of words.
- Counts the number of characters, including spaces.
- Handles empty input.
- Handles sentences with extra spaces.

## Test Results

### Test 1: Normal sentence

Input:

`First Python`

Result:

- Word count: 2
- Character count: 12

### Test 2: Empty input

Input:

`[Enter without typing anything]`

Result:

`You did not enter a sentence.`

### Test 3: Extra spaces

Input:

`   First Python   `

Result:

- Word count: 3
- Character count: 18 (Character count includes the extra spaces.)

## Limitation

The character count includes spaces, including leading and trailing spaces.

"# CSC649_First" 

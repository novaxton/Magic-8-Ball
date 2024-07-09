# Magic 8-Ball Program

## Overview

This simple Python program simulates a Magic 8-Ball, a popular toy used for fortune-telling or seeking advice. When run, it randomly selects and prints a message from a predefined list of possible responses, mimicking the behavior of a real Magic 8-Ball.

## Features

- **Random Message Selection:** The program randomly selects a message from a list of possible responses.

## Getting Started

### Prerequisites

- Python 3.x installed on your system.

### Running the Program

1. **Save the code** to a file, for example, `magic_8_ball.py`.
2. **Open a terminal** or command prompt.
3. **Navigate** to the directory where the `magic_8_ball.py` file is saved.
4. **Run the program** by typing:
   ```bash
   python magic_8_ball.py
   ```

### Code Explanation

The program performs the following steps:

1. **Imports the `random` module** to utilize its random number generation functionality.
2. **Defines a list of possible Magic 8-Ball messages**. These messages are common phrases you might find in a Magic 8-Ball.
3. **Prints a random message** from the list using `print()` and `random.randint()`. The `random.randint(0, len(messages) - 1)` function call generates a random index to select a message from the list.

### Example Output

When you run the program, you will see one of the following messages printed to the console:

- It is certain
- It is decidedly
- Yes definitely
- Reply hazy try
- Ask again later
- Concentrate and ask again
- My reply is no
- Outlook not so good
- Very doubtful

## Customization

You can customize the responses by editing the `messages` list. Add or remove messages as desired to tailor the output to your preferences.

# Mad Libs Game

A simple Python program that creates a fun Mad Libs story by taking user inputs for an adjective, two verbs, and a famous person's name.

## Features

- Prompts the user for an adjective, two verbs, and a famous person's name.
- Generates a humorous Mad Libs story using the provided inputs.
- Displays the generated Mad Libs story to the user.

## Installation

1. **Clone the repository:**

    ```
    git clone https://github.com/Rafsun07/madlibs-game.git
    cd madlibs-game
    ```

2. **Run the game:**

    ```
    python madlibs.py
    ```

## Usage

1. **Start the game:**

    Run the `madlibs.py` script to start the Mad Libs game.

    ```
    python madlibs.py
    ```

2. **Input Prompts:**

    The program will prompt you to enter an adjective, two verbs, and a famous person's name. For example:

    ```
    Adjective: funny
    Verb: run
    Verb: jump
    Famous person: Albert Einstein
    ```

3. **Output:**

    The program will generate and display a Mad Libs story using your inputs. For example:

    ```
    Computer programming is so funny! It makes me so excited all the time because I love to run. Stay hydrated and jump like you are Albert Einstein!
    ```

## How the Code Works

1. **Prompting for User Input:**

    The program starts by prompting the user to enter an adjective, two verbs, and a famous person's name. It uses the `input()` function to capture these inputs.

    ```
    adj = input("Adjective: ")
    verb1 = input("Verb: ")
    verb2 = input("Verb: ")
    famous_person = input("Famous person: ")
    ```

2. **Generating the Mad Libs Story:**

    Using an f-string, the program creates a Mad Libs story by inserting the user's inputs into a predefined template.

    ```
    madlib = f"Computer programming is so {adj}! It makes me so excited all the time because I love to {verb1}. Stay hydrated and {verb2} like you are {famous_person}!"
    ```

3. **Displaying the Story:**

    Finally, the program prints the generated Mad Libs story to the console.

    ```
    print(madlib)
    ```

This simple program demonstrates the basics of string interpolation and user input in Python, providing a fun way to engage with programming concepts.


## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code follows the project's coding standards and includes appropriate tests.

## Contact

For questions, suggestions, or issues, please open an issue on GitHub or contact the project maintainer at [rafsun.eram@gmail.com](mailto:rafsun.eram@gmail.com).

## Acknowledgements

- Developed using Python.
- Inspired by classic Madlibs game.

---

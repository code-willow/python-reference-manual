# 00 - Hello, World!

Welcome to your very first step in writing Python code! The "Hello, World!" program is a time-honored tradition for programmers learning a new language. It's simple, yet it confirms that your development environment is correctly set up and you can successfully execute code.

## What is "Hello, World!"?

The "Hello, World!" program is typically the simplest possible program that outputs the text "Hello, World!" to the console or screen. Its primary purpose is to:

1.  **Verify Environment Setup:** It's a quick check to ensure that your Python interpreter is installed correctly and that you can run Python scripts.
2.  **Introduce Basic Syntax:** It demonstrates the most fundamental command for outputting text in Python.

## Why "Hello, World!"?

This tradition dates back to the early days of programming. It's a universally recognized first step because it's minimal, focuses on the core task of output, and provides immediate, satisfying feedback that your tools are working. If you can get "Hello, World!" to print, you're ready for more complex tasks!

## The Code: `hello.py`

Let's look at the `hello.py` file in this folder:

```python
# This is a single-line comment.
# Comments are ignored by the Python interpreter and are used to explain the code.

# The 'print()' function is a built-in Python function.
# It is used to display output to the console (or screen).
# The text inside the parentheses and quotes is called a 'string literal'.
print("Hello, World!") # This comment explains what this specific line does.

# You can also use triple quotes for multi-line comments, though they are technically multi-line strings not assigned to a variable.
"""
This is a multi-line comment (or a multi-line string used as a comment).
It can span across multiple lines.
This program simply prints the classic "Hello, World!" message to the console.
It's often the first program new developers write to ensure their environment is set up correctly.
"""
```

### Key Takeaways from `hello.py`:

-   **`print()` function:** This is how you display output in Python. Whatever you put inside the parentheses `()` will be shown on your screen.
-   **String Literals:** The text `"Hello, World!"` is a "string literal." In Python, text is enclosed in single quotes (`'...'`) or double quotes (`"..."`).
-   **Comments:** These are lines in your code that the Python interpreter ignores. They are crucial for making your code understandable to humans (including your future self!).

    -   **Single-line comments:** Start with a hash symbol (`#`). Everything after `#` on that line is a comment.
    -   **Multi-line comments (Docstrings):** While technically multi-line strings, they are often used as comments when not assigned to a variable. They are enclosed in triple quotes (`"""..."""` or `'''...'''`).

## How to Run This Program

1.  **Open your terminal or command prompt.**
2.  **Navigate to this folder:**
    ```bash
    cd 01_Basics/00_Hello_World/
    ```
3.  **Run the Python script:**
    ```bash
    python hello.py
    ```

You should see `Hello, World!` printed to your console! Congratulations, you've run your first Python program!

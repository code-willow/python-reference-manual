# Setting Up Your Python Environment

Before you can start writing and running Python code, you need to set up your development environment. This involves installing Python and choosing a tool to write your code in. Let's get you set up!

## 1. Installing Python

Python is free and can be installed on Windows, macOS, and Linux.

### On Windows:

1.  **Go to the official Python website:** Open your web browser and navigate to [python.org](https://www.python.org/downloads/).
2.  **Download the installer:** The website should automatically detect your operating system and suggest the latest version of Python for you to download. Click the "Download Python" button.
3.  **Run the installer:** Once the download is complete, run the installer.
4.  **IMPORTANT:** On the first screen of the installer, make sure you check the box that says **"Add Python to PATH"**. This will make it much easier to run Python from the command line.
5.  **Complete the installation:** Click "Install Now" and follow the on-screen instructions.

### On macOS:

macOS usually comes with an older version of Python pre-installed. It's best to install the latest version.

1.  **Go to the official Python website:** [python.org/downloads/](https://www.python.org/downloads/)
2.  **Download the installer:** Download the latest version for macOS.
3.  **Run the installer:** Open the downloaded `.pkg` file and follow the installation instructions.

### On Linux:

Most Linux distributions come with Python pre-installed. You can check which version you have by opening a terminal and typing:

```bash
python3 --version
```

If you need to install it or upgrade, you can use your distribution's package manager. For example, on Debian/Ubuntu:

```bash
sudo apt update
sudo apt install python3
```

## 2. Verifying Your Installation

Once the installation is complete, you can verify that Python is installed correctly. Open your command prompt (on Windows) or terminal (on macOS/Linux) and type:

```bash
python --version
```

or on some systems

```bash
python3 --version
```

This should print the version of Python you just installed.

## 3. The Python Interpreter (REPL)

Python comes with a built-in interactive interpreter, also known as a **REPL** (Read-Eval-Print Loop). It's a great way to test small snippets of code.

To start the REPL, just type `python` or `python3` in your command prompt/terminal and press Enter. You should see something like this:

```
Python 3.14.0  (tags/v3.14.0:ebf955d, Oct  7 2025, 10:15:03) [MSC v.1944 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

The `>>>` is the Python prompt. You can type Python code here, and it will be executed immediately. For example:

```python
>>> print("Hello, World!")
Hello, World!
>>> 2 + 3
5
```

To exit the REPL, you can type `exit()` or press `Ctrl+Z` (on Windows) or `Ctrl+D` (on macOS/Linux).

## 4. Writing and Running Python Scripts

The REPL is great for quick tests, but for larger programs, you'll want to save your code in a file. Python files have the `.py` extension.

1.  **Create a file:** Open a plain text editor and create a new file.
2.  **Write some code:** Type a simple Python program, for example:

    ```python
    # hello.py
    print("Hello from a file!")
    ```

3.  **Save the file:** Save the file as `hello.py`.
4.  **Run the script:** Open your command prompt/terminal, navigate to the directory where you saved the file, and run it using the `python` command:

    ```bash
    python hello.py
    ```

    or

    ```bash
    python3 hello.py
    ```

    You should see the output `Hello from a file!` printed to the console.

## 5. Code Editors and IDEs

While you can write Python code in any plain text editor, using a dedicated code editor or an Integrated Development Environment (IDE) will make your life much easier. These tools provide features like:

- **Syntax Highlighting:** Makes your code more readable by coloring different parts of the syntax.
- **Code Completion:** Suggests code as you type.
- **Debugging Tools:** Helps you find and fix bugs in your code.
- **Integrated Terminal:** Allows you to run your code without leaving the editor.

### Popular Choices for Python:

- **Visual Studio Code (VS Code):** A free, lightweight, and highly extensible code editor from Microsoft. It's one of the most popular choices for Python development. You'll need to install the Python extension from the VS Code Marketplace.
- **PyCharm:** A powerful IDE specifically for Python, created by JetBrains. It comes in a free Community edition and a paid Professional edition.
- **Sublime Text:** A fast and lightweight code editor.
- **Atom:** Another free and open-source code editor.

**Recommendation for Beginners:** **Visual Studio Code** is an excellent starting point. It's easy to use, powerful, and has a huge community.

---

You are now all set up and ready to start your Python programming journey. In the next sections, we will finally start diving into the code!

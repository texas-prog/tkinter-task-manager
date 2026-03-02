# tkinter-task-manager

A lightweight, event-driven desktop application for managing daily tasks. Built entirely with Python's standard `tkinter` library, this project transitions from a basic command-line terminal script to a fully interactive Graphical User Interface (GUI).

## Features
* **Intuitive UI:** A clean, easy-to-use desktop window.
* **Add Tasks:** Quickly add new tasks to your list using the text entry box.
* **Select & Remove:** Click on any task in the listbox to highlight it, then easily remove it with a button click.
* **Input Validation:** Prevents adding blank tasks.
* **Error Handling:** Uses native OS pop-up alerts (message boxes) to warn users if they try to delete a task without selecting one first.

## Prerequisites
This application uses Python's built-in `tkinter` module, so no external third-party packages (like via `pip`) are required.

**Note for macOS (Homebrew) Users:** If you installed Python via Homebrew, the `tkinter` library is packaged separately. You may need to install it before running the app. For Python 3.13, run:
`brew install python-tk@3.13`

## How to Run
1. Clone this repository to your local machine:
   `git clone https://github.com/yourusername/python-todo-gui.git`
2. Navigate into the project directory:
   `cd python-todo-gui`
3. Run the Python script:
   `python app.py` *(replace `app.py` with the actual name of your python file)*

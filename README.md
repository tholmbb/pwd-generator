# Password generator

**pwdgenerator.py** is a simple Python script for generating random passwords.  
I created this tool for use at work, where I often need to manage multiple user accounts at once.

---

## Features

- Generate one or more strong passwords at a time
- Each password includes:
  - At least one uppercase letter
  - One number
  - One special character (`!` or `#`)
  - Additional randomized characters
- Output is printed to the terminal – easy to copy/paste

---

## To-Do / Future Ideas

- Add option to export generated passwords directly to a `.csv` file
- Add command-line arguments (e.g. password length)
- Support for different complexity levels (e.g. no special characters, min/max length)
- Turn into an installable package or CLI tool
- GUI

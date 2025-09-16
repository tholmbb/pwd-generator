# pwd-generator

**pwd-generator** is a simple Python script for generating random passwords.  
I created this tool for use at work, where I often need to manage multiple user accounts at once.

---

## Features

- Generate one or more strong passwords at a time
- Each password includes:
  - At least one uppercase letter
  - One number
  - One special character (`!` or `#`)
  - Additional randomized characters
- Output is printed cleanly to the terminal – easy to copy/paste or redirect

---

## To-Do / Future Ideas

- Add option to export generated passwords directly to a `.csv` file
- Add command-line arguments (e.g. password length, number of passwords)
- Support for different complexity levels (e.g. no special characters, min/max length)
- Clipboard integration (automatically copy first password)
- Turn into an installable package or CLI tool
- GUI version using Tkinter or PyQt
- Add unit tests for password generation logic
- Logging or verbose mode for debug purposes

# pwd-generator

**pwd-generator** is a simple Python script for generating secure random passwords.  
I created this tool for use at work, where I often need to manage multiple user accounts at once.

There are many password generators online, but this one fits my workflow:  
it allows me to quickly generate and copy multiple strong passwords at once, even into formats like CSV if needed.

---

## Why I Made This

In user account management, I often needed to create multiple passwords at once.  
Instead of generating them one by one or relying on online tools, this script helps me:

- Instantly generate 10+ secure passwords in one run
- Use consistent formatting and rules
- Easily copy them into other tools or files (e.g., CSV, provisioning scripts)

---

## Features

- Generate one or more strong passwords at a time
- Each password includes:
  - At least one uppercase letter
  - One digit
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

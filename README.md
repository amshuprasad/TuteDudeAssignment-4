## Task 1: Read a File and Handle Errors

### Objective:
The goal of this task is to read the content of a file named `sample.txt` and print its contents line by line. A key requirement is to handle the case where the file might not exist.

### Explanation:
- The program tries to open a file called `sample.txt` in read mode.
- If the file exists, it reads each line and prints it.
- If the file does not exist (i.e., `FileNotFoundError` is raised), the program catches the error and displays a user-friendly message instead of crashing.
- This demonstrates how to use `try-except` blocks in Python to write error-resilient code.

---

## Task 2: Write and Append Data to a File

### Objective:
This task focuses on writing user-provided content to a file named `output.txt`, appending additional content, and finally reading and displaying everything written to the file.

### Explanation:
- First, the program asks the user to enter some text and writes it to `output.txt`. If the file does not exist, it is created automatically.
- Then, it prompts the user for more input and appends that text to the same file.
- Finally, the program opens the file again in read mode, reads all the lines, and prints them to show the combined content.
- This task demonstrates how to use file modes (`"w"`, `"a"`, `"r"`) for writing, appending, and reading, respectively.
- It also illustrates how to interact with the user and manage file operations in sequence.



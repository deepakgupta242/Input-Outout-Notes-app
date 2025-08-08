# NotesManager

A simple Java console application for managing text-based notes. Notes are saved to and read from a file using `FileWriter` and `BufferedReader`.

## Features

- **Add Note:** Write a new note, which is appended to `notes.txt`.
- **View Notes:** Display all saved notes from `notes.txt`.
- **Exit:** Quit the application.

## How to Use

1. **Compile the code:**
    ```sh
    javac NotesManager.java
    ```

2. **Run the application:**
    ```sh
    java NotesManager
    ```

3. **Menu Options:**
    - Enter `1` to add a new note.
    - Enter `2` to view all notes.
    - Enter `3` to exit the application.

## File Storage

- Notes are stored in a file named `notes.txt` in the same directory as the program.
- Each note is saved on a new line.

## Example

```
Notes Manager
1. Add Note
2. View Notes
3. Exit
Choose an option: 1
Enter your note: Buy milk
Note saved.

Notes Manager
1. Add Note
2. View Notes
3. Exit
Choose an option: 2

Your Notes:
- Buy milk
```

## Requirements

- Java 8 or higher




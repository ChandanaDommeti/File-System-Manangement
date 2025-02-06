# File-System-Manangement

## Overview
This is a simple console-based file system simulation written in Java. It allows users to create, rename, delete, and view files stored in different directories (Desktop, Documents, and Pictures). The system provides a menu-driven interface for easy interaction.

## Features
- Create files and add them to a selected directory.
- Rename existing files.
- Delete files from directories.
- Print the list of files in a specific directory.
- User-friendly menu-driven interface.

## Technologies Used
- Java
- Data Structures: ArrayList
- Scanner for user input

## How to Run
1. Ensure you have Java installed on your system.
2. Compile the Java file:
   ```bash
   javac Filesystem.java
   ```
3. Run the program:
   ```bash
   java Filesystem
   ```
4. Follow the on-screen instructions to manage files.

## Usage
When the program starts, you will see the following menu:
```
Welcome
1: Create a file and add to a directory
2: Rename a file
3: Delete a file
4: Print files in a directory
5: Exit
Enter choice:
```
- Choose an option by entering the corresponding number.
- Follow the prompts to perform file operations.

## Example Interactions
### Creating a File
```
Enter File Name: myfile.txt
Select a directory to add the file:
1: Desktop
2: Documents
3: Pictures
Enter choice: 1
File added to Desktop.
```

### Renaming a File
```
Enter the current file name: myfile.txt
Enter the new file name: newfile.txt
File renamed successfully.
```

### Deleting a File
```
Enter the file name to delete: newfile.txt
File deleted successfully.
```

### Printing Files in a Directory
```
Select a directory to print:
1: Desktop
2: Documents
3: Pictures
Enter choice: 1
[File1.txt, File2.java]
```

## Future Improvements
- Implement a hierarchical directory structure with nested folders.
- Add file content storage and retrieval.
- Introduce user authentication for access control.


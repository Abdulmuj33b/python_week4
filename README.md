# python_week4
File Read & Write Function Documentation
Overview
The file_read_write() function reads the content of a user-specified file, modifies it by converting all text to uppercase, and saves the modified content in a new file. It incorporates error handling to manage various file-related issues.

Functionality
Prompts the user to enter the filename of an existing text file.

Reads the content of the specified file.

Converts the content to uppercase.

Saves the modified content in a new file prefixed with "modified_".

Handles exceptions to manage errors effectively.

Exception Handling
FileNotFoundError: Displays an error if the specified file does not exist.

PermissionError: Handles cases where the file cannot be accessed due to permission restrictions.

IsADirectoryError: Prevents attempting to read a directory instead of a file.

UnicodeDecodeError: Addresses issues when reading non-text files.

IOError: Catches general input/output errors related to file operations.

Exception: Handles any unexpected errors to enhance robustness.

Usage Example
To use this function, simply run:

python
file_read_write()
Then, enter the filename of a text file to modify and save its uppercase version.

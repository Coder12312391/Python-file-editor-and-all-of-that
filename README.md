• 'r' (Read): Opens a file for reading only. This is the default mode, and it raises a FileNotFoundError if the file does not exist.
• 'w' (Write): Opens a file for writing. It creates a new file if it does not exist, or completely erases (truncates) the file if it already exists.
• 'a' (Append): Opens a file for writing at the very end without erasing existing content. It creates a new file if it does not exist.
• 'x' (Exclusive Creation): Creates a new file and opens it for writing. It fails with a FileExistsError if the file already exists.

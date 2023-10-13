
## Basic Linux Commands Documentation

### 1. **ls**
   - **Description**: List files and directories in the current directory.
   - **Usage**: 
     ```
     ls [options] [directory]
     ```
   - **Options**:
     - `-l`: Detailed listing.
     - `-a`: Show hidden files.
     - `-h`: Human-readable file sizes.

### 2. **pwd**
   - **Description**: Print the current working directory.
   - **Usage**:
     ```
     pwd
     ```

### 3. **cd**
   - **Description**: Change the current directory.
   - **Usage**:
     ```
     cd /path/to/directory
     ```

### 4. **mkdir**
   - **Description**: Create a new directory.
   - **Usage**:
     ```
     mkdir directory_name
     ```

### 5. **touch**
   - **Description**: Create an empty file.
   - **Usage**:
     ```
     touch file_name
     ```

### 6. **cp**
   - **Description**: Copy files or directories.
   - **Usage**:
     ```
     cp source_file destination_directory
     ```
   - **Options**:
     - `-r`: Copy directories recursively.

### 7. **mv**
   - **Description**: Move or rename files or directories.
   - **Usage**:
     ```
     mv source_file destination
     ```

### 8. **rm**
   - **Description**: Remove files or directories.
   - **Usage**:
     ```
     rm file_name
     ```
   - **Options**:
     - `-r`: Remove directories recursively.

### 9. **cat**
   - **Description**: Display the contents of a file.
   - **Usage**:
     ```
     cat file_name
     ```

### 10. **more** and **less**
   - **Description**: Display file contents one screen at a time.
   - **Usage**:
     ```
     more file_name
     less file_name
     ```

### 11. **head** and **tail**
   - **Description**: Display the beginning or end of a file.
   - **Usage**:
     ```
     head file_name
     tail file_name
     ```

### 12. **grep**
   - **Description**: Search for text in files using patterns.
   - **Usage**:
     ```
     grep "pattern" file_name
     ```

### 13. **chmod**
   - **Description**: Change file permissions.
   - **Usage**:
     ```
     chmod permissions file_name
     ```

### 14. **ps**
   - **Description**: List running processes.
   - **Usage**:
     ```
     ps
     ```

### 15. **kill**
   - **Description**: Terminate processes.
   - **Usage**:
     ```
     kill PID
     ```

### 16. **man**
   - **Description**: Access the manual pages for commands.
   - **Usage**:
     ```
     man command_name
     ```

### 17. **df**
   - **Description**: Display disk space usage.
   - **Usage**:
     ```
     df
     ```

### 18. **du**
   - **Description**: Display file and directory space usage.
   - **Usage**:
     ```
     du
     ```

### 19. **tar**
   - **Description**: Archive and compress files.
   - **Usage**:
     ```
     tar options archive_name files/directories
     ```
   - **Options**:
     - `-c`: Create a new archive.
     - `-z`: Compress the archive using gzip.

### 20. **wget**
   - **Description**: Download files from the internet.
   - **Usage**:
     ```
     wget URL
     ```
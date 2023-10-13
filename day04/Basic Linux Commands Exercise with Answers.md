## Day04: Basic Linux Commands Exercise with Answers

**Objective**: Familiarize yourself with basic Linux commands.

**Tasks**:

1. **Navigation and File Management**:
   - Open a terminal window.
   - Navigate to your home directory.
   - Create a new directory called "linux_basics".
   - Enter the "linux_basics" directory.
   - Create three subdirectories: "documents", "pictures", and "code".
   - List the contents of the directory to verify the creation of these folders.

   **Solution**:
   ```bash
   cd ~
   mkdir linux_basics
   cd linux_basics
   mkdir documents pictures code
   ls
   ```

2. **File Creation and Manipulation**:
   - Create a new text file called "sample.txt" inside the "documents" directory.
   - Open "sample.txt" in a text editor (like `nano`, `vim`, or `gedit`).
   - Write a few lines of text.
   - Save and close the file.

   **Solution**:
   ```bash
   cd documents
   touch sample.txt
   nano sample.txt  # Add some text, then save and close the file.
   ```

3. **Copying and Moving Files**:
   - Create a copy of "sample.txt" inside the "code" directory.
   - Move the original "sample.txt" to the "pictures" directory.

   **Solution**:
   ```bash
   cp sample.txt ../code/sample_copy.txt
   mv sample.txt ../pictures/
   ```

4. **Viewing and Navigating Files**:
   - Navigate to the "code" directory.
   - View the contents of "sample_copy.txt" without opening it.
   - Return to the previous directory.

   **Solution**:
   ```bash
   cd ../code
   cat sample_copy.txt
   cd -
   ```

5. **Removing Files and Directories**:
   - Delete the "sample_copy.txt" file inside the "code" directory.
   - Remove the "code" directory.

   **Solution**:
   ```bash
   rm sample_copy.txt
   cd ..
   rmdir code
   ```

**Extra Challenge**:

6. **Wildcard Usage**:
   - Create three files in the "documents" directory: "file1.txt", "file2.txt", and "file3.txt".
   - Use a wildcard to delete all files in the "documents" directory that end with ".txt".

   **Solution**:
   ```bash
   cd documents
   touch file1.txt file2.txt file3.txt
   rm *.txt
   ```

7. **Permissions**:
   - Create a new directory called "private" inside "linux_basics".
   - Restrict access to only the owner of the directory.
   - Verify that only the owner can access the "private" directory.

   **Solution**:
   ```bash
   cd ..
   mkdir private
   chmod 700 private
   ls -l
   ```

⚠️ Important Warning: Exercise Caution!
Remember to always be cautious when running commands, especially those involving deletion or modification of files and directories. Double-check the commands before executing them.
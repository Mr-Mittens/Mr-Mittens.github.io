### Contents

- [Git](##Git-Cheat-Sheet)
- [Vim](##Vim-Cheat-Sheet)


## Git Cheat Sheet

### Initialization

#### 1. Check Git Version
```bash
git --version
```

#### 2. Initialize a Directory
```bash
mkdir sample           # Create a folder
cd sample              # Move to the directory
git init               # Initialize Git in the directory
```

### Configuration

#### 3. Configure Git
```bash
git config --global user.name "Your Username"
git config --global user.email "your.email@example.com"
```

### File Operations

#### 4. Create Files
```bash
touch sample.html      # Create an HTML sample file
touch sample.py
touch main.js
touch index.html
```

#### 5. Add Files
```bash
git add sample.html    # Add a specific file
git add .              # Add all files in the directory
```

#### 6. View Status
```bash
git status             # View current Git status
```

#### 7. Remove Files
```bash
git rm --cached index.html    # Remove a file from staging
```

### Commits and Branches

#### 8. Commit Changes
```bash
git commit -m "Your changelog"     # Commit changes
```

#### 9. Branches
```bash
git branch sample       # Create a branch
git checkout sample     # Switch between branches
git merge sample        # Merge branches
```

### Remote Repositories

#### 10. Add Remote URL
```bash
git remote add origin <repo-url>  # Add remote repository URL
```

#### 11. View Remote
```bash
git remote              # View remote repositories
```

#### 12. Push and Pull
```bash
git push -u origin master         # Push files to repository
git pull <repo-url>               # Pull changes from repository
```

#### 13. Cloning Repositories
```bash
git clone <repo-url>             # Clone a Git repository
```

#### 14. Removing All Files
```bash
git rm -f *             # Remove all files from Git repo
```



## Vim Cheat Sheet

### Beginner

#### Navigation

- **h, j, k, l**: Move left, down, up, right respectively.
- **w, e**: Move forward by word, move to the end of a word.
- **0, $**: Move to the beginning and end of a line.

#### Editing

- **i**: Enter insert mode before the cursor.
- **a**: Enter insert mode after the cursor.
- **x**: Delete the character under the cursor.
- **u**: Undo the last change.

#### Saving and Exiting

- **:w**: Save the file.
- **:q**: Close the file.
- **:q!**: Close the file without saving.

### Advanced

#### Copy, Paste, and Delete

- **yy**: Copy the current line.
- **dd**: Delete the current line.
- **p**: Paste after the cursor.
- **P**: Paste before the cursor.

#### Search and Replace

- **/pattern**: Search for a pattern.
- **:%s/old/new/g**: Replace all occurrences of 'old' with 'new'.

#### Multiple Files

- **:e file**: Open a new file.
- **:bn**: Move to the next buffer.
- **:bp**: Move to the previous buffer.

### Pro-vimmer

#### Macros

- **q{register}**: Start recording a macro into a register.
- **@{register}**: Execute a macro stored in a register.
- **@@**: Repeat the last run macro.

#### Split Windows

- **:split**: Split the window horizontally.
- **:vsplit**: Split the window vertically.
- **Ctrl + w + w**: Switch between windows.

#### Marks

- **m{letter}**: Set a mark at the current cursor position.
- **'{letter}**: Move to the line containing the mark.
- **:marks**: Display all marks.



`vim lifestyle` is the next level (will be updated when i reach beyond !) 
# Git, Github and Bash

This is a test line - don't ignore
This repo covers the following concepts/ tools:
  - Github
  - Git
  - Bash
  - README files
  - MarkDown or .md files


## Bash
Bash is a scripting language used by command line terminals.
We can use it to create file, navigate our computer or run programs.

### Basic Bash Commands
  ```
  cd        - changes directory
  ls        - lists all files
  mkdir     - makes directory
  rmdir     - removes directory (USE WITH CAUTION)
  touch     - creates file
  rm        - remove file
  echo      - prints a given variable or string

  ```
## Git
Git is version control.


### Basic Git Commands

  ```
  0) git init        -- initialise the timeline
  0) create .gitignore
  0) git log
  0)git status
  0) git remote add origin [url of repo] -- adds the url as the origin of current local repo


  1) git add <file> / git add . (adds all files in current folder)
  2) git commit -m 'initial commit'  -- commit file after adding it after modification

  3) git push -u origin master    -- pushes the commits to the online github repo

  ```
To update README or other files:
  ```

  1) git add .
  2) git commit -m 'commit title'
  3)git push -u origin master (assuming connection to origin is already established)
  ```

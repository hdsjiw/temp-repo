# Command Line Interface
### Version Control and Collaboration
  - Changes VS Snapshots

| **Changes**   | **Snapshots**  | 
| :----- | ----: | 
| Storing data as changes to the base version   | Storing data as snapshots | 
| Only the modified parts are recorded.  | The state of all files at a specific point in time is stored  | 

  - Local, Centralized, and Distributed Version Control
    1. Local Version Control : Each user has their own version database
    2. Centralized Version Control : Multiple users connect to a central VCS server to manage versions
    3. Distributed Version Control : Every user has an independent full version history
### Git
  - 3 States in Git
    - Modified : Working Directory
    - Staged : Staging Atrea
    - Committed : .git directory

### Git config
  - Git configuration levels
    1. System level : Affects all uses and repositories on the system
    2. Global(User) level : Affects all repositories of a current user
    3. Local level : Specific to the current repository
      
  - Git configuration setup
 ```sh
$ git config --global user.name "GITHUB NAME"
$ git config --global user.email "GITHUB EMAIL"
$ git config --global init.defaultBranch main
$ git config --list
$ git config --list --show-origin
$ git config user.name
 ```
  - .gitignore file
    
| **기호**   | **Meaning**  | 
| :----- | ----: | 
| *.a   | Ignore all .a files | 
| /TODO  | Only ignore the TODO file in the current directory |
| build/  | Ignore all files in any directory named build |
| doc/*.txt  | Ignore doc/notes.txt |
| doc/**/*.pdf  | Ignore all .pdf files in the doc/ directory and any of its subdirectories |
     
### Git Processing

 ```sh
$ git init # Initializing a Repository in an Existing Directory
 ```

 ```sh
$ git status # Checking Repository Status
 ```

 ```sh
$ git add [file name] # Adding a new file to be staged (tracked)
$ git add . # Adding every new file
 ```

 ```
$ git rm--cached [file name] # Unstaging a file
 ```

 ```sh
$ git commit -m “commit message” #Commit
 ```

 ```sh
$ git branch
$ git branch -m master main # Change branch name
 ```

 

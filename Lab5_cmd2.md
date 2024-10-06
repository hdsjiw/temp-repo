# Command Line Interface
### Output
  - Standard output : screen
  - File output : using ">" 
| **기호**   | **OUTPUT**  | 
| :----- | ----: |
| X | screen(default) |
| > | Create&Save file |
| >> | Append an existing file |

 ```sh
 ls -lh
 ls -lh > file_list.txt
 ls -lh >> file_list.txt
 ``` 

### Input

| **기호**   | **INPUT**  | 
| :----- | ----: |
| X | keyboard(default) |
| < | file |

### Pipeline
 "|" : Use to enter multiple commands at once\

### Shell Command
  - pwd : shows the current path in a hierarchical directory
   
  - cd : change directory
  - ls : list files/directories
  - 
| 기호 | mean  | 
| :----- | ----: |
| / | root |
| . | current directory |
| .. | upper-level directory |
| ~ | home of current user |  
| /[directory] | absolute path |  
| ./[directory] | relative path | 

| 기호 | mean  | 
| :----- | ----: |
| -l | detailed information |
| -lh | detailed information, human친화적인 |

  - cp : copy files/directories
 ```sh
$ cp file1 file2 
$ cp -i file1 file2
$ cp file1 dir1
$ cp -R dir1 dir2
 ```  
  - mv : move
 ```sh
 mv file1 file2
 mv -i file1 file2
 mv file1 file2 dir1
 mv dir1 dir2
 ``` 
  - rm : remove
 ```sh
 rm file1 file2
 rm -i file1 file2
 rm -r dir1 dir2
 ```
  - mkdir : make a new directory
  - clear : interface clean
  - exit

### Wildcards
  - \* : All filenames
  - g* : g로 시작하는 All filenames
  - Data??? : Begins with the characters "Data" followed by 3 more characters
### Others
  - tab : Autocompletion(자동 완성)
  - ↑ : past commands

### Help Command
  - help 명령어
  - man 명령어 : manual

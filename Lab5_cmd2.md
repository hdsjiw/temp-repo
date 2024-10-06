# Command Line Interface
### Output
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
"l" : Use to enter multiple commands at once

### Permissions
  - ***-rwxrwxrwx*** / ***-rw-r--r--***
    - ***-rwx*** : Read/Write/Execute for file owner
    - ***rwx*** : Read/Write/Execute for group owner
    - ***rwx*** : Read/Write/Execute for all user

| Value | Meaning | 
| :----- | ----: |
| 777 | rwxrwxrwx(No restrictions) |
| ***755*** | rwxr-xr-x(Common use) |
| 700 | rwx------ |
| 666 | rw-rw-rw- |
| 644 | rw-r--r-- |
| 600 | rw------- |

  - chmod : Changing permissions
 ```sh
chmod 644 words.txt
 ```
  - Superuser : All system adminstration authority
 ```sh
sudo 명령어
 ```
### Text Editors
| Name | description  | 
| :----- | ----: |
| ***vi,vim*** | cmd/ powerful, lightweight, and fast |
| Emace | cmd/ every feature |
| ***nano*** | cmd/easy to use-recommend for first-time users |
| gedit | gui/easy to use-recommend for first-time users |
| kwrite | gui/syntax highlighting |

### Shell Script
sh 스크립트 : Execute the command at once

### Others
  - echo : Output value of text or variable

```sh
 echo print out the text
 ``` 
  - "/" : enter(for long commands)
  - wget : download files from the internet directly

```sh
 wget 파일명
 ```
  - history : See previous command history
  - curl : fetching,uploading, and managing data
  - grep (Global Regular Expression Print) : Searching text within files

    ***Command options***
    
| **기호**   | **OUTPUT**  | 
| :----- | ----: |
| -i | Case-free search |
| -v | Not containing |
| -n | Display line numbers along with matching lines |
| -r | Recursive search(all files) |


  
| **기호**   | **OUTPUT**  | 
| :----- | ----: |
| .* | No matter |
| \d | Matches any digit |
| [abc] | Matches any single character within the braskets |
| ^ | Matches the beginning of a line |
| $ | Matches the end of a line |

### ***More information, ask to LLM!***

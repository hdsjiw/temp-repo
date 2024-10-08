<!--# My Project Plan (Level 1 Heading)
 ***Note:*** This document is written merely as an illustrative example, and does not provide
 any working guide to an actual project.
 
### Proposal (Level 3 Heading)
---
 I am planning to make a computer vision software that detects objects in images.
 In order to build it, I will use opencv, deep learning libraries, such as [TensorFlow](https://www.tensorflow.org/?hl=ko)
or [PyTorch](https://pytorch.org/), and other open source softwares.
 
 For example, the objects in the following images were detected using [mmdetection](https://github.com/open-mmlab/mmdetection):

![example](https://user-images.githubusercontent.com/12907710/137271636-56ba1cd2-b110-4812-8221-b4c120320aa9.png)

---

### Dependencies (Level 3 Heading)
  - python
  - opencv-python
  - tensorflow
  - openmmlab
  - package manager

 ### Installation (Level 3 Heading)
  In a bash terminal, run the following commands *(Do NOT actually run these commands in
  your computer)*:
 ```sh
$ sudo apt update 
$ conda create -n cv_detection 
$ conda activate cv_detection 
$ python --version 
$ python example.py
 ```
-->
# Command Line Interface
### Kernal and Shell
| **Kernel**   | **Shell**  | 
| :----- | ----: | 
| Core of OS  | Allows users to communicate with kernel | 
| Managing HW resources  | Give commands  | 

### CLI VS GUI

| **CLI**   | **GUI**  | 
| :----- | ----: |
| Command Line Interface | Graphical User Interface |
| Remember commands | Easy to use, intuitive |
| Keyboards | Mouse |
| Fast | Slow |
| Remember commands | Easy to use, intuitive |

### Git Bash
 Git Bash is a command-line interface application that provides a Git command-line experience with a Bash emulation on Windows. It's often used by developers to interact with Git repositories in a Linux-like environment, even on a Windows system.
 
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
$ mv file1 file2
$ mv -i file1 file2
$ mv file1 file2 dir1
$ mv dir1 dir2
 ``` 
  - rm : remove
 ```sh
$ rm file1 file2
$ rm -i file1 file2
$ rm -r dir1 dir2
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

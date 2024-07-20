# **Google Python Exercises**

## Overview
The solutions to the Google Python Developer course exercise issued for the summer semester of 2024 in the Advanced Programming course at THD Cham Campus are available in this repository.
The practice questions center on fundamental Python concepts, including lists, strings, dictionaries, files, regular expressions, and utilities.

There are four exericises consisting nine coding exercise. 
 - Basic Exercise 
    - Learnt about the topics string, list, sorting in the   coding exercise files string1.py, string2.py, list1.py and list2.py
    - And the topics Mimic.py and Wordcount.py works on Dictionaries and files.
 - Babynames
    - Learnt about topics of regular expression file operation containing read and write operation
 - Logpuzzle
   - Learnt about the topics Regular expression file operations containing read and write operation and HTML file creation
 - Copyspecial
   - Learnt about the topics like Regular expression file operation containing read and write operation and Utilities

---
# Steps for Installation
 - Download the Google Python Exercises from <https://developers.google.com/static/edu/python/google-python-exercises.zip>
 - Download the IDE of your choice (eg: VS Code <https://code.visualstudio.com/download>)
 - Download the GitHub Desktop <https://desktop.github.com/>
 - Install VScode and Git Hub imn your desktop
 - Create a repostiory in the github for the Google Python exercise and add the exercise files to it.
 - Download and Install Python from <https://www.python.org/ftp/python/3.12.4/python-3.12.4-amd64.exe>
 - Download and install git bash from <https://git-scm.com/downloads>
 - Install the required libraries or plugins, such as Python, the Git extension from VScode (such as Start git-bash), Python, Git History and Python Debugger, before beginning to solve the problem.

 ---

 # Plugins and Libraies Used
  - Python Version - 3.12.4
  - VS Code for Windows
  - GitHub for Windows
  - Git for Windows
  - Extension used in VS Code 
     - Start git-bash, Python, Git History, Pylance, Python Debugger.
---
# Coding guidelines used
- The variables are given descriptive names that accurately capture the nature of the issue.
- Brief and simple comments are added 
- The variable are named using the **Snake Case** naming convention.
- The code sample for the practices used is shown below.
```
python

def build_word_count(text):
  
  # Builds a dictionary where keys are words and values are word counts.

  words = text.lower().split()
  word_count = {}
  for word in words:

    if word in word_count:
      word_count[word] += 1
    else:
      word_count[word] = 1
  return word_count
```
---
# Author
Harinesh Balamurugan (12405137) [harinesh-balamurugan](https://github.com/harinesh-balamurugan)

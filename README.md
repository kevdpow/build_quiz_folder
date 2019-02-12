# build_quiz_folder
This Python 3 script builds a ready-to-quiz folder for Geeks Who Drink Quizmasters.

## Requirements
1. [Python 3.5 or Later](https://www.python.org/downloads/)

2. [LXML](https://lxml.de/installation.html)

    Windows:
    
    <code>py -3 -m pip install lxml</code>
    
    UNIX:
    
    <code>python3 -m pip install lxml</code>

3. Quiz ZIP folder as distributed by Geeks Who Drink on OBYQM.

## Setup

**Be sure to add an 'r' in front of Windows paths!**

1. Open build_quiz_folder.py
2. Add path to your audio clips folder on line 11. 
3. Add path to your master score sheet at line 12.
4. Save the script.

## Run
1. Open Command Prompt / Terminal
2. <code>cd path/to/script/folder</code>
3.  Run Command
    
       Windows: 
    
       <code>py -3 build_quiz_folder.py C:\path\to\quiz.zip</code>
    
       UNIX: 
    
       <code>python3 build_quiz_folder.py path/to/quiz.zip</code>

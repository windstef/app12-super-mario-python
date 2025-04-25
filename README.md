# Super Mario Implementation in Python

This is inspired by Meth-Meth-Method's [super mario game](https://github.com/meth-meth-method/super-mario/)

## Running

* $ pip install -r requirements.txt
* $ python main.py

## Standalone windows build

* $ pip install py2exe
* $ python compile.py py2exe

## Controls

* Left: Move left  
* Right: Move right  
* Space: Jump  
* Shift: Boost   
* Left/Right Mouseclick: secret   

## Current state:
![Alt text](img/pics.png "current state")

## Dependencies	
* pygame	
* scipy	

## Contribution

If you have any Improvements/Ideas/Refactors feel free to contact me or make a Pull Request.
The code needs still alot of refactoring as it is right now, so I appreciate any kind of Contribution.


# Section 44: Day 44: App 12 - Code Review: The Mario Game

## 363. Programming Tool of the Day: Collaborating

### Keynotes

1. Provided the github repository
https://github.com/arditsulceteaching/super-mario-python
2. Fork this repository to my github account
3. Clone the forked repository to my local IDE
4. Do some changes
5. Commit and push the changes to my repository
6. Create Pull Request of the commit(s) to notify the
other user to review and approve the changes
7. For smaller teams just clone the repository and
commit/push the changes directly to the repository.


## 364. Setting up the Project Locally

### Keynotes

1. Install the list of requirements mentioned in the file
_requirements.txt_
2. via command line
`pip install -r requirements.txt`
3. An error thrown:
  error: subprocess-exited-with-error
  
  × python setup.py egg_info did not run successfully.
  │ exit code: 1
  ╰─> [33 lines of output]
...
4. The dependencies are installed from the IDE successfully.
Installed packages: 'pygame==2.1.2', 'scipy==1.9.3'
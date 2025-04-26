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


## 365. Inspecting the Project Structure

### Keynotes

1. _compile.py_
convert the Python project into an executable
2. _main.py_
the entry point of the program
3. _requirements.txt_
contains the required libraries to be installed
4. _settings.json_
contains some general settings about the game, e.g. sound effect, music on/off
5. folder: _classes_
each class in a single file for readability a.s.o
file name is the class name
6. folder: _entities_
similar as classes
7. suggestions: 
a. classes and entities file names to be in lowercase
b. the folders' names to be renamed in some more specific meaning
8. folder: _img_
it contains the images are stored
9. folder: _levels_
it contains the data in json files. Reflect to the level of the game
10. folder: _sfx_
it contains the sound/audio files are located
11. folder: _sprites_
it contains images with data, e.g. background tiles
12. folder: _traits_
it contains the features that a player gets, e.g. jump higher


## 366. Inspecting the Code

### Keynotes

1. inspect the _main.py_
2. the code is contained in the function _main()_ when the file is executed directly
3. To discover from where a method is called from the drop-down menu select:
_Find Usages_ and follow the chain of calls
4. Also, after _Find Usages_ click on the _Call Hierarchy_, and in reverse order
5. In a file, class, choose the _Structure_ tool to inspect it.
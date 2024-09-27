# Licence-Plates-Challenge
Detection of License Plates

## Code structure

## How To Use
To clone and run this project, you will need Git and Conda installed on your computer.
An alternative of conda is have installed the packages on the environment.yml file.

If you have Conda installed, from your command line write the following instructions to create an environment with all the dependencies and then activate it:

```bash
# Clone this repository
$ git clone https://github.com/saraxmartin/Licence-Plates-Challenge

# Go into the repository
$ cd License-Plates-Challenge

# Creating the environment with the provided environment.yml file
$ conda env create --file environment.yml

# Activating the environment
$ conda activate license_plates

# For running the project
py main.py
```

If you have trouble activating the environment and the error that shows up says something like:

-  Your shell has not been properly configured to use 'conda activate'

Do this instructions in the terminal:
```bash
# To know which type of shell you have 
$ echo $SHELL

# IF the output of the command above is for example: /bin/bash  

# To initialize the shell 
$ conda init bash

# To activate the environment
$ conda activate license_plates
```

If you are in Visual Studio Code, you would have to select the interpreter manually. To select the interpreter of the environment, press 'Ctrl+Shift+P', search 'Python: Select interpreter' and click on the environment interpreter.
If you can't see the interpreter, in the terminal write
```
which python
```
Copy the path that output. Press again 'Ctrl+Shift+P', press in 'Enter interpreter path' and paste the path you have copied before.



In case that you can't see all the branches, run the command:
```bash
git fetch --all
```
## Pytesseract Installation Guide
To succesfully install Pytesseract you must download the program from the following [link](https://github.com/UB-Mannheim/tesseract/wiki)

## Contributors
Sara Martín Núñez -- Sara.MartinNu@autonoma.cat
Iván Martín  Campoy -- ivan.martinca@autonoma.cat
Aina Navarro Rafols -- Aina.NavarroR@autonoma.cat

Vision and Learning
Degree in Artificial Intelligence
UAB, 2024-25


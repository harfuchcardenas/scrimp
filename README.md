scrimp [sc-(reen) - (g)-imp)]

Command invented 

# Scrimp

Scrimp is a program designed by the need of printing a snapshot of the screen with a linux command written in perl.
You need to have installed all the required dependencies like "Perl,, to be installed before to run successfully this pregram.


## Features

- Feature 1: takes a screen shot from a pointer that needs to get clicked and hold in order to select an area on the screen.
  Useful when watching videos and need to take notes as it then opens gimp in order to edit the image right away.
- Feature 2: Deallocates the memory of the used screenshot.png file used only temporarily. 

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone git@github.com:<your-username>/scrimp.git
``
move dependencies to bin folder that is included in the PATH variable.
   2. sudo cp scrimp/scrimp /usr/local/bin
   3. sudo cp scrimp/screenshot /usr/local/bin
   4. sudo cp scrimp/editfile /usr/local/bin
Turn the files into executables.
   5. chmod +x /usr/local/bin/scrimp
   6. chmod +x /usr/local/bin/screenshot
   7. chmod +x /usr/local/bin/editfile
   8. sudo source /usr/local/bin/scrimp

## Run
   ```
   scrimp
  ```

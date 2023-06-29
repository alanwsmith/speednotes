-> title

h (for your personal help files)


-> h2

Overview

This goal of this project is to make a simple command
called `h`` that runs from the command line. It displays
the content of text files. The idea is to make 
little cheat sheets and get to them quickly.


-> h2

Usage


-> code
>> shell 

h whatever


-> h2

Current Status


-> todo 

[x] store files in `~/.h-files`` 

[x] show `~/.h-files/default.txt`` if no arguments
    are passed to the command

[x] show a file if an argument with the same name
    is passed (e.g. `h whatever`` displays 
    `~/.h-files/whatever.txt``

[] update to list out all files if the `h`` command is
   run by itself

[] setup a way to open the files in an editor
   (e.g. `h --edit whatever``)

[] autocomplete file names from in the arguments 

[] make the ~/.h-files directory if it doesn't 
   already exist


-> h2

Installation

This is currently in the "Works on my machine" 
phase. If you clone the repo down on mac and run 
the install with this it's got a good chance of 
adding it to your path so you can use it:

-> code
>> shell 

cargo install --path .




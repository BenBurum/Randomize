Randomize
=========

File Randomizer in Java

What it is
==========

This program is designed to add a 4-digit random number to the beginning of a list of file names with the purpose of creating a randomized playlist for media players that don't have a random or shuffle function.  It also has functionality to revert the files to their original names.

How it works
============
Enter the directory which contains your files in the field labeled "Directory to Change:"
You can also navigate to the directory by selecting "Find Directory" from the File menu.

Next you need to enter the extensions of the files you want randomized in the field labeled ".ext"
You can enter the extensions in the field manually, or load a saved .txt file by either entering the path of the file in the field next to the "load" button and clicking load, or navigating to the file by selecting "Load Extensions File" from the File Menu.
MAKE SURE EVERY FILE EXTENSION IS ON ITS OWN LINE, OR IT WILL NOT BE READ BY THE PROGRAM!

Press the "Randomize!" button to add random numbers to the beginning of the files.  A special character, ")" will also be added.

Press the "deRandomize!" button to revert every file in the selected folder to its original name.  This works by looking for the special character ")" in the 5th character position of the file name, and deleting everything up to and including it.  THIS MEANS THAT IF YOU HAVE ANY OTHER FILES IN THE SELECTED FOLDER WITH ")" AS THEIR 5TH CHARACTER, THEY WILL BE RENAMED.  BE CAREFUL!
Every file in the selected folder will be deRandomized, regardless of what extensions are selected.

Thanks for trying my program!

-Ben

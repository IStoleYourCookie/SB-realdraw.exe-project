# SB-realdraw.exe-project
A Github repository for my SB (small basic) code

This is a console-based primitive drawing application capable of saving and loading files, aswell as simulating Langton's ant

You can compile the code online at 

https://superbasic-v2.azurewebsites.net/ 

or download the Small Basic compiler at 

https://smallbasic-publicwebsite.azurewebsites.net/assets/SmallBasic_v1.2.msi

# Inputs

new: makes a new grid, clears the visible space

w: moves the cursor up

s: moves the cursor down

a: moves the cursor left

d: moves the cursor right

e: draws a 'fill' character, and cycles between those 'fill' characters

q: draws a 'clear' character, and cycles between those 'cleat' characters

f: turns on the fill toggle, uses the current fill character

c: turns on the clear toggle, uses the current clear character

v: turns off any toggles, returnes to normal char-by-char(normal) mode

negate: changes every fill charater to the current clear character and vise versa, in the visible space

ant: starts a Langton's ant simulation with the current grid as the starting configuration, will ask for how many steps would you like to simulate

save: saves the visible space in a simple .txt format to C:\ directory, will ask for file name

exp_save: an experimental save procedure that tries to save not just the visible space, but the entire positive-positive quadrant

load: loads a savefile(or any file, that has two numbers as the first two rows, because the save format works like that), will ask for which file would you like to load

set_ant_face: sets Langon's ant direction, will ask for a number(input should be 1, 2, 3 or 4, if not, the ant will not move, only invert the cell beneath it)

---------------------------
Langton's ant facing system:        (X is the ant)

                              3
                              
                            4 X 2
                            
                              1
                              

## Useful Vim commands that I should know
-----------------------------------------------------

## Insert Mode
------------------------------
i - insert infront of the selected character
I - insert at the front of the line
a - insert after the selected character
A - insert at the end of the line
o - new line below cursor
O - new line above cursor

## Motion 
------------------------------
h - move left  
j - move down  
k - move up  
l - move right  
s - delete character under cursor and enter insert mode  
^ - move to the first non-blank character of a line  
$ - go to end of line without going into insert mode  
0 - go to beginning of line without going into insert mode  
H - go to top of current window  
zz - center text on screen  
M - go to middle of window  
G - move to the last line of the file  
gg - go to the first line in the file (can also put a number in front to go to that line ex. 15gg will take you to line 15.)
w - move to start of next word
W - move to start of next WORD
e - move to end of next word
E - move to end of next WORD (skips whitespace)
b - move to front of last word
-- you can do stuff like 5w, which will move forward 5 words

## Search and Find
------------------------------
f - find character ex. "fa" will find the next and hover over next a
t - find character ex. "ta" will find the next a and put the cursor before it

/{word} - this will search for a word
n - go down to the next word searched
N - go up to the next word searched

## Copy, Cut and Paste
------------------------------
yy- copy full line (copy multiple lines with numbers ex. 3yy)
yw- copy word
dd- cut line
dw - cut word
p - paste after cursor
P - paste before cursor


# vieditor
vi editor reference
VIM - Vi Improved is an text editor 

VIM - has 3 modes
1) Write mode
2) Command mode
3) Command-line mode

Write Mode
==========
Insert 
	- i - insert left side of the cursor 
	- a - append to the right side of cursor
	- o - insert below the line ( new line )
	- I - Beginning of the line
	- A - End of the Line
	- O - Above the line
	
Cursor 
	- j - Down
	- h - left
	- k - up
	- l - right
	- G - End of the line
	- :10 - 10th line
	- :n - nth line
	
Update
	- cw - change word
	- C - Change entire line
	- r - replace one char
	- R - Replace till esc is pressed 
	
Delete
	- dw - delete word
	- d4w - delete 4 words
	- dd - delete line
	- 5dd - delete 5 lines
	
cut paste and copy paste
	- dw - cut | p - paste
	- dd - cut | p - paste
	- yy - copy | p - paste

	-J - join the lines
	
Command mode: esc + : 
	- w - write
	- q - quit
	- q! - force quit
	- wq - write and quit
	- wq! - force write and quit
	- set nu  - set line number
	- syntax on
	- 
	http://trainings.bkpit.com

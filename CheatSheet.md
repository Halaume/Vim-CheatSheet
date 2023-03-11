# Vim cheatsheet
#### Vim is a very efficient text editor. This reference was made for Vim 8.0.
#### For shortcut notation, see :help key-notation. (I will eventually add the table of all of them at the end of this CheatSheet)

#	GLOBAL

##	Exiting
|	Cmd		|	Purpose	|
|	:----:	|	----:	|
|`:q`		|Close file	|
|`:qa`		|Close all files	|
|`:w` / `:x`|Save and close file	|
|`ZZ`		|Save and quit	|
|`ZQ`		|Quit without checking changes	|

##	Exiting insert mode
|	Cmd		|	Purpose	|
|	:----:	|	----:	|
|`Esc` / `<C-[>`	|Exit insert mode	|
|`<C-C>`	|Exit insert mode, and abort current command	|

##	Clipboard
|	Cmd		|	Purpose	|
|	:----:	|	----:	|
|`x`	|Delete character	|
|`dd`	|Delene line (Cut)	|
|`yy`	|Yank line (Copy)	|
|`p`	|Paste	|
|`P`	|Paste before	|
|`"*p` / `"+p`	|Paste from system clipboard	|
|`"*y` / `"+y`	|Paste to system clipboard	|

##	Find & Replace
|	Cmd		|	Purpose	|
|	:----:	|	----:	|
|`:%s/foo/bar/g`|Replacce foo with bar in whole document	|

##	Navigating
|	Cmd		|	Purpose	|
|	:----:	|	----:	|
|`h` `j` `k` `l`|Arrow keys	|
|`<C-U>` / `<C-D>`	|Half-page up/down	|
|`<C-B>` / `<C-DF>`	|Page up/down	|
###### |word|
|try|oui|

##	Editing

##	Visual mode


#	OPERATORS

##	Usage

##	Operators list

##	Exemples


#	TEXT OBJECTS

##	Usage

##	Diff

##	Text objects

##	Exemples


#	MISC

##	Folds

##	Windows

##	Tags

##	Misc

##	Command line

##	Text alignment

##	Calculator

##	Exiting with an error

##	Navigation

##	Jumping

##	Counters

##	Case

##	Marks

##	Spell checking

>	All of this is from vim.rtorr.com and devhints.io/vim.

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

###### Words

|	Cmd		|	Purpose	|
|	:----:	|	----:	|
|`b` / `w`	|Previous/next word	|
`ge` / `e`	|Previous/next end of word	|

###### line

|	Cmd		|	Purpose	|
|	:----:	|	----:	|
|`0`	|Start of line	|
|`^`	|Start of line (after whitespace)	|
|`$`	|End of line	|

###### Character

|	Cmd		|	Purpose	|
|	:----:	|	----:	|
|`fc`	|Go forward to character c	|
|`Fc`	|Go backward to character c	|

###### Document

|	Cmd		|	Purpose	|
|	:----:	|	----:	|
|`gg`	|First line	|
|`G`	|Last line	|
|`:{number}`	|Go to line {number}	|
|`{number}G`	|Go to line {number}	|
|`{number}j`	|Go down {number} lines	|
|`{number}k`	|Go up {number} lines	|

###### Window

|	Cmd		|	Purpose	|
|	:----:	|	----:	|
|`zz`	|Center this line	|
|`zt`	|Top this line	|
|`zb`	|Bottom this line	|
|`H`	|Move to top of screen	|
|`M`	|Move to middle of screen	|
|`L`	|Move to bottom of screen	|

###### Search

|	Cmd		|	Purpose	|
|	:----:	|	----:	|
|`n`	|Next matching search pattern	|
|`N`	|Previous match	|
|`*`	|Next whole word under cursor	|
|`#`	|Previous whole word under cursor	|

###### Tab pages

|	Cmd		|	Purpose	|
|	:----:	|	----:	|
|`:tabedit [file]`	|Edit file in a new tab	|
|`:tabfind [file]`	|Open file if exists in new tab	|
|`:tabclose`	|Close current tab	|
|`:tabs`	|List all tabs	|
|`:tabfirst`	|Go to first tab	|
|`:tablast`	|Go to last tab	|
|`:tabn`	|Go to next tab	|
|`:tabp`	|Go to previous tab	|


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

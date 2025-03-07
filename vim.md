*vim language*

:find -command is used to find any file in vim
:ls -gives the list of the open buffer's of the vim
:b buffer_name -jumps to the open buffer of the vim
* to make it fuzzy
hit tab to :find by partial match

autocomplete-
^x^n for just this file.
^x^f for filenames
^x^] for tags
^o^n^p for language specific completion
^n for anything specified by the complete option
use ^n and ^p to go back and forth in suggestion list 

make program-
:make executes the file
:cn and :cp to navigate forward and back
:cl to list errors
:cc# to jump to error by number

navigation command:
(within a line)
ctrl+w deletes word by word
ctrl+shift+- undoes the changes
beginning of line: 0
first char of line: ^
end of line: $
last char on line: g_
iw inner word(works from anywhere in a word)
it inner tag(the contents of a html tag)
i" inner quotes
ip inner paragraph
as a sentence
f,F,t,T find the next character
/ search

(basic navigation command)
j means naviagtion down
k means navigation up
h means navigation left
l means navigation right
d deletes
c changes(delets and changes to insert mode)
> indent
v visually select
y yank(copy)
w word
b back
nj down n lines
ctrl+w to move among the splits

(line navigation)
first line,last line,like number: g,G,ngg
top of the screen: H
middle of the screen: M
bottom of the screen: L

(screen navigation)
current line to top,middle,bottom: zz and z.,zt,zb
scroll one line: ctrl+y(moves the page down) and ctrl+e(moves the page up)
scroll halfpage: ctrl+u(up) and ctrl+d(down)
scroll full-page: ctrl+b(backward) and ctrl+f(forward)

(extra navigation)
n% moves to that percent of the file
* navigates with the same word thoughout the file in forward
# navigates with the same word thoughout the file in backward
dw deletes samll word
e navigates through the words in forward motion
diW deletes large word
dB deletes the word till the cursor
m<letter> sets the mark
b'<leter> navigates to the exact same line
'<letter> navigates to the first line of the paragraph
. to perform the last step again
cw changes a word
"<letter>p prints whatever is in the register <letter>
ctrl+r <letter> does the same but while in insert mode
ctrl+a inserts the last inserted text



this were very basic vim keybindings,now start creating on top it,create your own shortcuts and have fun!!!

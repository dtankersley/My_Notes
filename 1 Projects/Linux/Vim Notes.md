* Learn to navigate with hjkl
  h = left
* j = down
* k = up
* l  = right

==Normal Mode==

x = delete
       d   motion

  Where:
    d      - is the delete operator.
    motion - is what the operator will operate on (listed below).

  A short list of motions:
    w - until the start of the next word, EXCLUDING its first character.  (dw)
    e - to the end of the current word, INCLUDING the last character. (de)
    $ - to the end of the line, INCLUDING the last character. (d$)

  Thus typing  de  will delete from the cursor to the end of the word.

NOTE:  Pressing just the motion while in Normal mode without an operator will
       move the cursor as specified.

dw = delete word (move cursor  to the word you need to delete and type 'rw')
d$  = delete a whole line of textjjj

i  = edit at the begiining of a line
A = Edit at the END of a line

:q! = quit without saving
:wq = save/write changes and quit

USING A COUNT FOR A MOTION


   ** Typing a number before a motion repeats it that many times. **

  1. Move the cursor to the start of the line below marked --->.

  2. Type  2w  to move the cursor two words forward.

  3. Type  3e  to move the cursor to the end of the third word forward.

  4. Type  0  (zero) to move to the start of the line.



# VIM

## Exit

* Press the `<ESC>` key (to make sure you are in Normal mode).
* Type: `:q! <ENTER>`.

NOTE: `:q! <ENTER>` discards any changes you made.

## Navigate

### Left / down / up / right

To move the cursor, press the h,j,k,l keys as indicated.

```
      ^
      k              Hint:  The h key is at the left and moves left.
< h       l >               The l key is at the right and moves right.
      j                     The j key looks like a down arrow.
      v
```

## Save changes

Save the file with changes and exit Vim with: `:wq <ENTER>`

## Insert

### Before character

* Move the cursor on top of the character before you want to insert text.
* Press `i` to insert text.

### After character

* Move the cursor on top of the character after you want to insert text.
* Press `a` to insert text.

### Before line 

* Move the cursor to the line where you want to append text. It does not matter on what character the cursor is in that line.
* Press `I` to insert text.

### After line 

* Move the cursor to the line where you want to append text. It does not matter on what character the cursor is in that line.
* Press `A` to insert text.

### New line

* Press `o` to insert new line below the cursor.
* Press `O` to insert new line above the cursor.

## Delete

### Delete a character

* Move the cursor until it is on top of the character you want to delete.
* Press `x` to delete the character under the cursor.

### Delete a word

* Move the cursor to the beginning of a word that needs to be deleted.
* Type `dw` to make the word disappear.

### Delete to the end of line

* Move the cursor to the place on the that needs to be deleted.
* Type `d$` to delete to the end of the line.

## Operators & motions

### Delete

Many commands that change text are made from an operator and a motion.
The format for a delete command with the `d` delete operator is as follows:

`d motion`

Where:

* d - is the delete operator.
* motion - is what the operator will operate on (listed below).

A short list of motions:

* w - until the start of the next word, EXCLUDING its first character.
* e - to the end of the current word, INCLUDING the last character.
* $ - to the end of the line, INCLUDING the last character.

### Use a count for a motion

Typing a number before a motion repeats it that many times:

* Type `2w` to move the cursor two words forward.
* Type `3e` to move the cursor to the end of the third word forward.
* Type  `0` (zero) to move to the start of the line.
* Type `d2w` to delete the two words.

### Delete lines

* Type `dd` to delete the line.
* Type `2dd` to delete two lines.

## Undo command

* Type `u` to undo the last command executed.
* Type `U` to return the line to its original state.
* Type `CTRL-R` (keeping CTRL key pressed while hitting R) a few times to redo the commands (undo the undos).

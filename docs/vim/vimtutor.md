# VIM

## Exit

1. Press the `<ESC>` key (to make sure you are in Normal mode).
2. Type: `:q! <ENTER>`.

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

## Insert

### Before character

1. Move the cursor on top of the character before you want to insert text. 
2. Press `i` to insert text.

### After character

1. Move the cursor on top of the character after you want to insert text. 
2. Press `a` to insert text.

### Before line 

1. Move the cursor to the line where you want to append text. It does not matter on what character the cursor is in that line.
2. Press `I` to insert text.

### After line 

1. Move the cursor to the line where you want to append text. It does not matter on what character the cursor is in that line.
2. Press `A` to insert text.

### New line

1. Press `o` to insert new line below the cursor.
2. Press `O` to insert new line above the cursor.

## Delete

### Delete a character

1. Move the cursor until it is on top of the character you want to delete.
1. Press `x` to delete the character under the cursor.

### Delete a word

1. Move the cursor to the beginning of a word that needs to be deleted.
2. Type `dw` to make the word disappear.

### Detelete to the end of line

1. Move the cursor to the place on the that needs to be deleted.
2. Type `d$` to delete to the end of the line. 

### Save changes

Save the file with changes and exit Vim with: `:wq <ENTER>`

## TBD
Lesson 1.2.3: ON OPERATORS AND MOTIONS

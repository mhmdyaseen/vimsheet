# My Vim Cheatsheet

## Exiting
- `:q` - Quit  
- `:w` - Save (write)  
- `:wq` / `:x` - Save and quit  
- `:q!` - Quit without saving  

---

## Navigation
- `h` / `<backspace>` - Move left  
- `j` / `<enter>` - Move down  
- `k` - Move up  
- `l` / `<space>` - Move right  

- `w` - Next word  
- `b` - Back to the previous word  
- `e` - Next last letter of the word  
- `ge` - Last letter of the previous word  

---

## Editing
- `a` - Append from current position  
- `A` - Append from the end of the line  
- `i` - Insert mode  
- `o` - Insert a new line below and enter insert mode  
- `O` - Insert a new line above and enter insert mode  
- `x` - Delete character without entering insert mode  
- `s` - Delete character and enter insert mode  
- `S` - Delete the entire line and enter insert mode  
- `dd` - Delete the current line  
- `C` - Delete from the current position till the end of the line (EOL) and enter insert mode  
- `r` - Replace one character without entering insert mode  
- `R` - Enter replace mode until `Escape` is pressed  
- `u` - Undo changes  
- `<Ctrl> + r` - Redo changes  

---

## Copy & Paste
- `yy` - Copy the current line  
- `p` - Paste below the current line  
- `P` - Paste above the current line  
- `"+p` - Paste from the system clipboard (anti-clockwise)  
- `"+y` - Copy to the system clipboard (anti-clockwise)  

---

## Scroll
- `<Ctrl> + u` - Scroll half a page up  
- `<Ctrl> + d` - Scroll half a page down  
- `<Ctrl> + b` - Scroll a full page up  
- `<Ctrl> + f` - Scroll a full page down  

- `zz` - Center the current line  
- `zt` - Move the current line to the top of the screen  
- `zb` - Move the current line to the bottom of the screen  

---

## Quick Move
- `gg` - Go to the first line  
- `G` - Go to the last line  
- `:line_number` - Go to a specific line number  

- `0` - Move to the start of the line  
- `^` - Move to the start of the line after whitespace  
- `$` - Move to the end of the line  

- `fc` - Go forward to character `c` in the line  
- `Fc` - Go backward to character `c` in the line  

---

~ Road under construction..

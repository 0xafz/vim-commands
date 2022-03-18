- **Note:** some of them are compatible with nvim only.
- ## Search 

  1. `/\C<search_word>` for case senstive search

- ## Insert around selection

  1. Only In visual Mode,after selection press `S` and insert character.

- ## Help

  1. :help quickref

- ## Find and Replace

  1. `/<existing word>` => `cgn<desired word>` => `.` to replace next <existing word> with <desired word>
  2. `:%s/foo/bar/g`
  3. For specific lines: `:6,10s/foo/bar/g`

- ## Copying and cutting in normal mode

  1. `yy or Y` – yank the current line, including the newline character at the end of the line
  2. `y$` – yank to the end of the current line (but don't yank the newline character); note that many people like to remap `Y` to `y$` in line with C and D
  3. `yiw` – yank the current word (excluding surrounding whitespace)
  4. `yaw` – yank the current word (including leading or trailing whitespace)
  5. `ytx` – yank from the current cursor position up to and before the character (til x)
  6. `yfx` – yank from the current cursor position up to and including the character (find x)
  7. [Check for more](https://vim.fandom.com/wiki/Copy,_cut_and_paste)
  8. [ Sublime-Like cursor Editing ](https://stackoverflow.com/questions/11784408/vim-multiline-editing-like-in-sublimetext)

- ## Command History

  1.press `q:` to open **Command History** and `:q` to close it.



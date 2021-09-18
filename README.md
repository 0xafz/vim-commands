# vim-commands

- ## Search

  1. /\c<search_word> for case insenstive search

- ## Indentation

  1. `gg=G`. `gg` to get the start of the file, `=` to indent,`G` to the end of the file.

- ## Reloading

  1. reloading the current file -> `:e` or `:edit`.

- ## Insert around selection

  1. Only In visual Mode,after selection press `S` and insert character.

- ## Help

  1. :help quickref

- ## Changing a word at n positions

  1. `/<existing word>` => `cgn<desired word>` => `.` to replace next <existing word> with <desired word>

- ## Copying and cutting in normal mode

  1. `yy or Y` – yank the current line, including the newline character at the end of the line
  2. `y$` – yank to the end of the current line (but don't yank the newline character); note that many people like to remap `Y` to `y$` in line with C and D
  3. `yiw` – yank the current word (excluding surrounding whitespace)
  4. `yaw` – yank the current word (including leading or trailing whitespace)
  5. `ytx` – yank from the current cursor position up to and before the character (til x)
  6. `yfx` – yank from the current cursor position up to and including the character (find x)
  7. [Check for more](https://vim.fandom.com/wiki/Copy,_cut_and_paste)
  8. [ Sublime-Like cursor Editing ](https://stackoverflow.com/questions/11784408/vim-multiline-editing-like-in-sublimetext)

- ## Moving lines up or down

  1. [Check](https://vim.fandom.com/wiki/Moving_lines_up_or_down#:~:text=In%20normal%20mode%20or%20in,to%20move%20the%20block%20up.)

- ## Command History

  1.press `q:` to open **Command History** and `:q` to close it.

- ## Editing multiple files

  1. `:tabe path-to-file`

- ## Snippets

  1. `/.config/coc/ultisnips/` or `:CocCommand snippets<TAB>`

- ## Emmet

  1. `emmet-expr` and type `ctrl-y,`

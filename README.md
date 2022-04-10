- **Note:** some of them are compatible with nvim only.
- ## Search

  - `/\C<search_word>` for case senstive search
  - place cursor on word and do `Shift+#` for next matching word

- ## Insert around selection

  - Only In visual Mode,after selection press `S` and insert character.

- ## Help

  - :help quickref

- ## Find and Replace

  - `/<existing word>` => `cgn<desired word>` => `.` to replace next <existing word> with <desired word>
  - `:%s/foo/bar/g`
  - For specific lines: `:6,10s/foo/bar/g`

- ## Copying and cutting in normal mode

  - `yy or Y` – yank the current line, including the newline character at the end of the line
  - `y$` – yank to the end of the current line (but don't yank the newline character); note that many people like to remap `Y` to `y$` in line with C and D
  - `yiw` – yank the current word (excluding surrounding whitespace)
  - `yaw` – yank the current word (including leading or trailing whitespace)
  - `ytx` – yank from the current cursor position up to and before the character (til x)
  - `yfx` – yank from the current cursor position up to and including the character (find x)
  - [Check for more](https://vim.fandom.com/wiki/Copy,_cut_and_paste)
  - [ Sublime-Like cursor Editing ](https://stackoverflow.com/questions/11784408/vim-multiline-editing-like-in-sublimetext)

- ## Command History

  -press `q:` to open **Command History** and `:q` to close it.

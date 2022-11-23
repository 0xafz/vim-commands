- **Note:** some of them are compatible with nvim only.
- ## Search

  - `/\C<search_word>` (`\C` for case senstive search)
  - `?\C`<search_word> backward search
  - `:noh` to turn off highlighting until the next search:
  - place cursor on word and do `Shift+#` for next matching word
  
- ## Vertical [motion](https://vimhelp.org/motion.txt.html#up-down-motions)
  
  - `j`for down, `k` for up
  - `:[line_number]` 
  - `}` to down until first empty line , `{` to up until first empty line
  - `[[`/`gg` for start of page, `]]`/`GG` for end of page

- ## Horizontal [motion](https://vimhelp.org/motion.txt.html#left-right-motions)

  - `h` for left, `l` for right
  - `f[any_letter]` To find and place cursor on given letter, `;` to repeat previous **f** action
  - `t[any_letter]` To find and place cursor on letter before given letter, `;` to repeat previous **t** action
  - `0` To the first character of the line
  - `^` To the first non-blank character of the line, `$` To the end of the line

- ## Insert around selection

  - Only In visual Mode,after selection press `S` and insert character.

- ## Help

  - :help quickref

- ## Find and Replace

  - `/<existing word>` => `cgn<desired word>` => `.` to replace next <existing word> with <desired word>
  - `:%s/foo/bar/gci` ([More info](https://stackoverflow.com/a/61357487))
    - `g` => global search
    - `c` => ask for confirmation first
    - `i` => case insensitive
  - For specific lines: `:6,10s/foo/bar/g`
  - Using `Shift + v` (Visual Mode)
    - After Selection, do `:s/foo/bar/gci`

- ## Copying and cutting in normal mode

  - `yy or Y` – yank the current line, including the newline character at the end of the line
  - `y$` – yank to the end of the current line (but don't yank the newline character); note that many people like to remap `Y` to `y$` in line with C and D
  - `yiw` – yank the current word (excluding surrounding whitespace)
  - `yaw` – yank the current word (including leading or trailing whitespace)
  - `ytx` – yank from the current cursor position up to and before the character (til x)
  - `yfx` – yank from the current cursor position up to and including the character (find x)
  - [Check for more](https://vim.fandom.com/wiki/Copy,_cut_and_paste)
  - [ Sublime-Like cursor Editing ](https://stackoverflow.com/questions/11784408/vim-multiline-editing-like-in-sublimetext)
- ## Copy,Cut and Paste from System registers
  
  - `"*`, `"+` are known as system clipboard registers. So you can do `"*y`,`"+y` to yank into / `"*p`,`"+p` to paste from system clipboard.
  
- ## Multiple copying
  
  - `"[any_letter]y` to yank/`"[any_letter]p` to paste 
  - ### Clearing custom registers (Not system)
    - `q[any_letter]q`
  
- ## Marking text in visual mode
  - `v` - start visual mode, mark lines, then do command (such as y-yank)
  - `V` - start Linewise visual mode
  - `o` - move to other end of marked area
  - `Ctrl+v` - start visual block mode
  - `O` - move to Other corner of block
  - `vaw` - mark a word
  - `vab` - a () block (with braces)
  - `vaB` - a {} block (with brackets)
  - `vib` - inner () block
  - `viB` - inner {} block
  - `Esc` - exit visual mode

- ## Command History

  -press `q:` to open **Command History** and `:q` to close it.
  
- ## Further reading
- [Basic Vim cheatsheet](https://www.worldtimzone.com/res/vi.html)

---
title:  Emacs Shortcuts
author: Daniel Weibel
date:   29 December 2016
last_updated: 29 December 2016
---

- Session
    - C-x C-c
        - Quit
    - C-z
        - Suspend (go back to shell, restart Emacs session with 'fg')

- Windows
    - C-x 0
        - Close the current window
    - C-x 1
        - Close all but current window
    - C-x 2
        - Split current window horizontally
    - C-x 3
        - Split current window vertically
    - C-x 4 C-f
        - Split current window horizontally and open specific file in new window
    - C-x o
        - Select the next window
    - C-M-v
        - Scroll forward one screen in the next window

- Files
    - C-x C-f
        - Open/new file
    - C-x C-s
        - Save file
    - C-x C-b
        - List buffers
    - C-x b
        - Switch to a certain buffer
    - C-x s
        - Interactively decide to save each buffer containing unsaved changes

- Navigation
    - C-v | PageUp
        - Scroll forward one screen
    - M-v | PageDown
        - Scroll backward one screen
    - C-p | ArrowUp
        - Previous line
    - C-n | ArrowDown
        - Next line
    - C-b | ArrowLeft
        - One character backward
    - C-f | ArrowRight
        - One character forward
    - M-b
        - One word backward
    - M-f
        - One word forward
    - C-a
        - Beginning of line
    - C-e
        - End of line
    - M-a
        - Beginning of sentence
    - M-e
        - End of sentence
    - M-<
        - Beginning of buffer
    - M->
      - End of buffer
  - C-s
      - Start incremental search (forward)
  - C-r
      - Start incremental search (backward)
  - C-M-s
      - Start regular expression incremental search
  - M-g g
      - Go to line (requires prefixed numeric argument)
  - C-<Space>
      - Set mark
  - C-u C-<Space>
      - Cycle through the last 16 marks
  - C-x C-x
      - Jump to last mark

- Text editing
  - Notes:
      - "kill" = "cut" (text saved to clipboard)
- "kill ring" = "clipboard" (but kill ring may hold multiple entries)
  - <Back>
      - Delete character to the left of cursor
  - C-d
      - Delete character to the right of cursor
  - M-<Back>
      - Kill word to the left of cursor
  - M-d
      - Kill word to the right of cursor
  - C-k
      - Kill from cursor until end of line
  - M-k
      - Kill from cursor until end of sentence
  - C-w
      - Kill text in region ("cut")
  - M-w
      - Add text in region to kill ring ("copy")
  - C-y
      - Yank top entry of kill ring ("paste")
  - M-y
      - Replace yanked text with next entry of kill ring
  - C-x u | C-_
      - Undo
  - M-q
      - Re-fill paragraph (with Auto-Fill minor mode in Text major mode)
  - M-%
      - Interactive search and replace

- Regions
  - C-x h
      - Select the entire buffer
  - M-h
      - Select the current paragraph
  - C-x n n
      - Narrow buffer to the current region
  - C-x n w

- Named extend commands (preceded by M-x)
  - replace-string
      - Find/replace after the cursor until end of file
  - load-file
      - Load a file (e.g. ~/.emacs)
  - re-builder
      - Testing regexes in separate window
  - occur
      - Display all lines matching a regex in a separate window
  - shell
      - Start a shell within Emacs
  - calculator
      - One-line calculator
  - pwd
      - Print working directory
  - cd
      - Change working directory
  - list-packages
      - List all installable packages (add package archives in init file)
  - package-install
      - Install an additional Emacs package
  - customize
      - Browse and set Emacs customisation variables
  - customize-browse
      - Browse all Emacs customisation variables on a single screen
  - customize-face
      - Browse and set faces (fonts, colours)

- Help
  - C-h C-h | C-h ?
      - Display help options
  - C-h t
      - Open tutorial
  - C-h c
      - One-line description of a command
  - C-h k
      - Documentation of a command in a new window
  - C-h f
      - Documentation of an Elisp function in a new window
  - C-h r
      - Open the Emacs manual
  - C-h a
      - Show Elisp functions matching a keyword or regex
  - C-h m
      - Description of major mode and enabled minor modes
  - C-h C-f
      - Emacs FAQ

- Misc
  - C-u <number> | M-<number>
      - Set numeric argument for subsequent command
  - C-g
      - Cancel command
  - <Esc><Esc><Esc>
      - All-purpose "get out" command
  - C-x f
      - Set column margin (requires prefixed numeric argument)
  - M-:
      - Evaluate Elisp expression
  - M-! | M-x shell-command
      - Execute a shell command and display output in new buffer
  - M-| | M-x shell-command-on-region
      - Execute a shell command piping in the current region as input
  - <F3>
      - Start recording macro
  - <F4>
      - Stop recording or play back macro (accepts numeric argument)
  - <Tab>
      - Move cursor to next button or editable field
  - <Shift>-<Tab>
      - Move cursor to previous button or editable field

- Key notation
  - C
      - Control
  - M
      - Meta (typically Alt/Option)
  - S
      - Shift
  - DEL
      - Backspace (not Delete)
  - RET
      - Enter
  - SPC
      - Space
  - ESC
      - Escape
  - TAB
      - Tab

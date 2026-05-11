# Acerbic Editing

Quite often you will have structured data that you want to make templated edits to all at once.  For example, if you have a struct definition or a JSON file and you want to use all of the fields in a large variable declaration.

Visual Studio Code has some great shortcuts that make this fun and easy.

[Acerbic Editing.webm](https://github.com/user-attachments/assets/9f3b4d5f-1348-4d94-bae6-83e4ba73638e)

Think in melody.  What words do you have, and what are you trying to change?

- `⌘` + `D`: Create additional cursor at next match for selection
- `⎇` + `Click`: Create additional cursor at pointer
- `⌘` + `⎇` + `↑`/`↓`: Create additional cursor on line above/below
- `⎇` + `←`/`→`: Navigate cursor left/right one word at a time
- `Shift` + `←`/`→`: Select under cursor
- `⎇` + `↑`/`↓`: Move line up/down
- `⌘` + `delete`: Delete all left
- `⌘` + `fn` + `delete`: Delete all right
- `⌘` + `shift` + `P`: Open Command Palette
  - `Transform to Uppercase`
  - `Transform to Lowercase`

Grab the edge of a common word and hit `⌘` + `D` a few times, move around with `⎇` + `←`/`→`.

With these shortcuts, you can make rapid edits to many lines with similar words and tabular layout.

# Insert Mode

## General Info
- Visual mode operates differently if it's linewise or characterwise, but with the overall similarity that you're pre-selecting text for your operator to work with.
- There is also Visual-Block mode, which allows you to edit rectangular blocks of text.
- You can use any nav commang, such as `<j>`, `<gg>`, or `</>`, to select text in Visual Mode
- The spot where you enter visual mode is 'fixed', and when you nav around, it moves the "free" end, highlighting everything in between.
- You can enable a more "regular" mode of editing by turning Visual Mode into Select mode with <C-g>`, but there's no need to do so.

## Tips
- Repeat actions on visual selections: if your last action was on a visual selection, `.` will repeat the action on the same selection.
- Prefer operators to visual commands when possible, however, because dot command will repeat on the same visual unit of text, e.g. three characters, instead of until the end of the (longer) line.
- Edit tabular data with visual block mode.
- Append to after ragged visual blocks with some operators like `$`, which will still do what you want, though the wordwise ones like `e` will keep it rectangular.

## Other things I learned

- Visual Mode commands

| Command | Effect |
|---------|--------|
| `V`       | enter linewise Visual mode |
| `v`       | enter characterwise Visual mode |
| `<C-v>`   | enter Visual-Block mode |
| `gv`      | repeat the last visual selection |
| `o`       | 'fix' the free end of the current visual selection, move to the other end, and free it |




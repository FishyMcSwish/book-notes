# Insert Mode

## Tips

- Use delete commands from insert mode without leaving Insert mode.  When you screw up a word, delete the whole word and retype it.  You will improve as a typist and it will become faster.
- Switch back to Normal mode frequently.  Switching to Insert Normal mode lets you fire one Normal Mode command without leaving Insert mode, with `<C-o>`
- Paste from a register without leaving Insert mode with `<C-r>`{register}
- Put stuff in the expresion register with <C-r>`=.  E.g., you can do math!  Try <C-r>`={6+5}`<CR>`
- Insert characters by unicode hex code with `<C-v>u{4 digit code} from insert mode, e.g. ୩
- Or <C-v>'U{up to 8 digits} to get a longer hex code that includes emoji.  🤣
- You can do digraphs from Insert mode with <C-k>'{char1}{char2}.  See :h digraphs-default, or :digraphs, :digraphs-table.  ©



## Other things I learned

- Here are some Insert mode commands for quick deletion. They work in the bash shell too (and IIRC they are also Emacs commands).

| Command | Effect |
|---------|--------|
| `<C-h>` | backspace |
| `<C-w>` | delete back one word|
| `<C-u>` | Delete back to the start of the line | 

- Ways to switch to Normal mode

| Command | Effect |
|---------|--------|
| `<Esc>` | Switch to Normal mode |
| `<C-[>` | Switch to Normal mode |
| `<C-o>` | Switch to Insert Normal mode |


- Other commands I learned

| Command | Effect |
|---------|--------|
| `zz` | Scroll current line to the middle of the screen |
| `<C-r>`{register} | paste from register while in Insert mode |




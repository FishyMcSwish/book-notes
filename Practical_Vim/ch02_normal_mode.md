# Normal Mode

## Tips

- It's best to "rest with your brush off the page" in normal mode
- Chunk your changes for to control the granularity of the undo and dot commands.  Often whatever counts as a "thought" is a good chunk size, e.g. a sentence or line of code.
- Compose repeatable changes.
- Use counts to do cool stuff like use incr/decr to do simple arithmetic
- Use counts vs repeats strategically.  Counts chunk undos cohesively, but are less granular and more prone to error.
- Combine operators and motions 


## Other things I learned

- Moving around in Insert mode w/arrow keys makes a new chunk for the purposes of 'u' or '.'
- when you use an operator, you briefly enter Operator Pending mode.  It waits for a motion, then returns to Normal mode and does the operation.
- you can duplicate all the operators to do a thing to a whole line. below are some operators i didn't know.

| Trigger | Effect |
|---------|--------|
| gu | make lowercase|
| gU | make uppercase
| > | shift right |
| < | shift left |
| = | autoindent | 

## Noteworthy plugins mentioned
- Commentary is a plugin that provides a custom operator to comment lines in languages supported by Vim
- vim-textobj-entire is a plugin that gives custom motions to work with the whole file

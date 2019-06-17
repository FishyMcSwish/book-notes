#NOTES FROM THE VIM WAY#

##Commands##

>G: indent to the end of the file


## Compound Commands##

C = c$
s = cl
S = ^C
I = ^i
A = $a
o = A<CR>
O = ko


##Repeater Commands##

/ = search forward.  n = next, N = last
? = search backward.  n = next, N = last
:s/target/replacement = substitute in the line.  & repeats
qx{changes}q = do series of changes.  @x repeats
(q and @ are doing register stuff, check out the help)


##Search##

* = search for word under cursor
:%s/target/replacement[/gc] = search/replace. g=global, c = confirm first.  g and c are optional.


##General Notes##

this chapter is all about making stuff repeatable.
so e.g., put pads around the '+'es in a line,
do f+ to find it, then do "s ' + '", then you can dot the command.


the ideal is:
1. do one action to move, like a search or f, that you can repeat with ;/,/n
2. do one repeatable action to execute your change
3. repeat your move, and repeat your change

In the book, this is called "The Dot formula"


##Other stuff I learned##

:edit <file> edits a file in this window
<C-w>[Arrow] moves within windows in a buffer
after f or F, ',' goes in the opposite direction

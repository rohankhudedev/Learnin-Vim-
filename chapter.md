# the secret sauce

- text objects

```
w - words
s - sentences
p - para
t - tags
```

- Motions
```
a - all
i - in
t - til
f - find forward
F - find backward
mk - mark position for track back. `k - go back to last marked position
```

- Combine with commands
```
d - delete
c - change
y - yank(copy)
v - visually select
```
- {command} {text obejct or motion}
```
diw - delete in word
caw - change in word
yi) - yank all text inside parentheses
va" - visually select all inside doublequotes including doublequotes
```
- Additional commands

```
o/O - create immediate newline with insert mode
dd / yy - delete/yank the current line
D / C - delete/change until end of line
^/$   - move to the beginning /end of line
I/A   - move to the beginning/end of line and insert
V j  - visual select line, j select next line and so on
u - undo
^r - redo
```

- The DOT command
```
. - just repeat last executed command
```

#### Macros

- Record a macro
```
q{register}
(do the things)
q
```
- Play a macro
```
@{register
```

- other
```
^A - increment number
^x - decrement number
^x - decrement number
^x - decrement number
```

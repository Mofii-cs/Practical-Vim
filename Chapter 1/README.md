## The Vim Way
### Tip 1 - The dot command
* repeat last change
```
[Command] x - delete the character under the cursor
```
```
[Command] u - undo the change
```
```
[Command] dd - delete the current line
```
```
[Command] >G - increase the indentation from the current line to the end of the file
```
* from the moment we enter Insert mode until we return to Normal mode, Vim records every keystroke. After making a change such as this, the dot command will replay our keystrokes.
### Tip 2 - Don't repeat yourself
```
[Command] j$. - 'j' moves the cursor down one line, '$' moves it to the end of the line, '.' buys us (a;<Esc>)
```
### Reduce Extraneous Movement
```
[Command] a - append after the current cursor position
```
```
[Command] A - append at the end of the current line
```
* 'A' = '$' + 'a'

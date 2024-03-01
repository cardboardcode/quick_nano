## **What Is This?** 
This document contains a simplified **cheat sheet** showing users how to use nano efficiently.

## **Why Use Nano?** :open_book:
Although you can use your own IDE, nano is a lightweight text editor that comes in-built into default Ubuntu. 

> In other words, if you need to edit files frequently in Docker images like me, you will find nano far more convenient. 

Docker does not support GUIs inherently and it is a pain to configure it to support that. :drop_of_blood:

## **Terminal Tricks** :computer:

`nano <file_name> -l`: Show the line number when nano editor is used.

`nano <file_name> --mouse`: Allow scrolling and clicking to be done via the mouse.

`nano <file_name> --softwrap`: Display overlong lines on multiple rows.

## **Keyboard Shortcuts** :keyboard:

`Ctrl` + `o`: Write to the file.

`Ctrl` + `x`: Exit nano editor.

`Ctrl` + `k`: Cut the line which the cursor is on out.

`Ctrl` + `u`: Paste the line that was cut earlier.

`Ctrl` + `w`: Register a string to search.

`Alt` + `w`: Repeat previously-registered search term.

`Ctrl` + `v`: Page down or skip multiple lines at one go.

`Alt` + `u`: Undo previous edit.

## Syntax Highlighting :rainbow:

Follow the instructions below to include specific code-specific syntax highlighting features.

### Markdown
```bash
sudo wget https://github.com/serialhex/nano-highlight/raw/master/markdown.nanorc -P /usr/share/nano/
``` 

### Python
```bash
sudo wget https://github.com/serialhex/nano-highlight/raw/master/python.nanorc -P /usr/share/nano/
```

### C/C++
```bash
sudo wget https://github.com/serialhex/nano-highlight/raw/master/c.nanorc -P /usr/share/nano/
```

## **TODO** :scroll:

- [x] Include instructions on how to have code-specific syntax highlighting.
- [x] Include instructions on how to navigate in nano editor for swiftly.
- [x] Include instructions/commands to edit `/etc/nanorc` to include soft-wrap and other features. 
- [ ] Display whitespace in editor so as to avoid python.

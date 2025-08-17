# How to create a file using Terminal
![Terminal](https://plus.unsplash.com/premium_photo-1678565999588-08fdd0b1410b?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8dGVybWluYWwlMjBjb2Rpbmd8ZW58MHx8MHx8fDA%3D)
## Open the terminal application
### macOS
Press `Command` + `Space` to open the Spotlight and search for `Terminal`.
### Windows
Use the system search to launch the `Terminal` application.

## Terminal interface
When opening the Terminal, it should look like this: 
![Terminal](https://pages.git.generalassemb.ly/modular-curriculum-all-courses/intro-to-the-cli/fundamentals/assets/terminal.png)
+ The arrow `->` means it is ready to receive an input.
+ the tilde `~` shows the current location in the system.

## Creating directories
To create directories, we use the `mkdir` command.

***Example***
```
mkdir terminal
```
Running this command will create a `terminal` directory.

Ones the directory is created, we will run the `cd` command to get into our new direcotry.

***Example***
```
cd terminal
```

## Touch
The `touch` command should be created in the directory we created with `mkdir`.

The `touch` command creates an empty file, with any extension. Such as, `.html` for a HTML file, `.txt` for a text file, `.png` for an image file, etc.

***Example***
```
touch index.html
```
Once the file is created, we can `code .` to start coding.

For more information on creating files using Terminal, visit [MDN Command Line](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Environment_setup/Command_line).

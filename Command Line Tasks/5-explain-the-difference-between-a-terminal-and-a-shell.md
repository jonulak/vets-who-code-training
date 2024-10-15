# Terminal vs Shell

## The Terminal

### What is a terminal? 

A terminal is an interface that allows a user to interact with a computer by entering commands. Historically, a terminal was a physical device with a keyboard and display. What we commonly think of today as the terminal is more specifically called a terminal emulator and is software meant to emulate the functionality of a hardware terminal.

### Roles of the terminal

- Accepts commands from the user and displays the output
- Acts as an interface between the user and the shell

### Types of terminals

- **Hardware terminals:** Physical devices with a keybaord and display
- **Terminal emulators:** Software that emulates the function of a hardware terminal. Examples include iTerm2, Windows Terminal, & GNOME Terminal.

## The Shell

### What is a Shell?

A shell is a command line interpreter that processes commands from the user and returns the results. It accepts commands and translates them into instructions that the kernel can understand and execute.

### Roles of a Shell

- Accepts commands entered by the user and translates them into executable actions
- Provides a scripting language for automation
- Interacts with the kernal to carry out tasks

### Types of Shells

- [**Bash** (Bourne Again Shell)](https://en.wikipedia.org/wiki/Bash_(Unix_shell)) is one of the most popular shells and is the default shell for many Linux distributions
- [**Fish** (Friendly Interactive Shell)](https://github.com/fish-shell/fish-shell) is a user-friendly shell that includes features like syntax highlighting, autosuggestions, and command completion
- [**Zsh** (Z shell)](https://en.wikipedia.org/wiki/Z_shell) is an extended version of Bash which offers improved features like auto-completion and customization options

## Interaction Between Terminal and Shell

### Communication

The terminal and shell work together, but are distinct components from one another. The terminal is the interface for typing commands and viewing output, but it does not process commands by itself. The shell receives input from the terminal, interprets it, executes the necessary commands or programs, and then sends the results back to the terminal to be displayed.

### Dependency

The terminal and shell are dependent on one another in that a terminal cannot function without a shell and a shell cannot receive input or display output without the terminal. However, they are also independent of each other as a terminal emulator can be used to interact with different types of shells. For example, the Terminal app on macOS can be used with bash, zsh, fish, or many other shells.

## Sources

1. [Computer terminal - Wikipedia](https://en.wikipedia.org/wiki/Computer_terminal#Emulation)
1. [Shell (computing) - Wikipedia](https://en.wikipedia.org/wiki/Shell_(computing)#Command-line_shells)
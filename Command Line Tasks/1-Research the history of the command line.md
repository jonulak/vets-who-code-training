# History of the command line interface

## Origins
The Command Line Interface (CLI) originated in the 1950s and 60s as an interactive replacement for previous interfaces such as punch cards. The earliest iterations were used in Teletype (TTY) machines as a way to send commands using a typewriter like interface. Primitive CLIs were also used in time sharing systems such as Compatible Time-Sharing System (CTSS) which used a text based interface to execute commands.[[1](#sources)]

## Early CLI Evolution
Following more primitive implementations of CLIs in the 1950s, the first implementation resembling a modern CLI came with Multics in 1964. The Multics shell supported "active functions" which could return strings that could be substituted as input for other commands.[[2,3](#sources)]

In 1971, Ken Thompson at Bell Labs would model the first Unix shell off of the Multics shell. The Thompson shell introduced a compact syntax for redirecting the input and output of a command as well as the concept of pipes with allowed passing the output of one command to the input of another.[[4](#sources)]

The Thompson shell would be succeeded in 1977 by the Bourne shell (sh). Developed by Stephen Bourne at Bell Labs, the Bourne shell was intended as a scripting language in addition its use as a command line interpreter, allowing scripts to be written and run from files. The Bourne shell was very influential and would become the model for the development of several other shells, including the C shell developed by Bill Joy a graduate student at the University of California, Berkley. The C shell was designed to have syntax more similar to the C language and also introduced a number of interactive features common today such as the command line history and aliases.[[5,6,7](#sources)]

## Open Source Contributions
In 1983, Richard Stallman announced the GNU Project with the goal of collaboratively devloping and publishing software that was free to use and distribute. To achieve this goal, the project began development of the GNU operating system and in 1988 funded the development of the Bourne-again shell (Bash) as a free replacement for the Bourne shell. Bash would become one of the first programs ported to the open source operating system Linux by Linus Torvalds and the development of Linux and similar open source OSes would fuel the growth of command line tools and shells.[[8,9](#sources)]

## Modern CLIs
The use of CLIs became less frequent beginning in the 1980s as software and operating systems implemented more intuitive graphical user interfaces (GUIs). Despite this, the CLI still maintains relevance for use in advanced computing tasks. The entire feature set of an operating system may not be available through the GUI, for instance. 

Additionally, CLI use is still preferred by many technical professionals due to increased efficiency and the ability to automate tasks which cannot be done with a GUI. For these reasons, even modern operating operating systems still include command line tools such as terminal on macOS and PowerShell on Windows. Furthermore, with the widespread use of cloud computing and microservices the CLI has become more important as these services provide powerful CLI tools for managing cloud services and automating the deployment of resources.


## Key Milestones

| Year | Event |
| ---- | ----- |
| 1964 | Louis Pouzin coined the term *shell* for a command line interpreter separate from the OS kernel & his ideas are implemented in the Multics shell by Glenda Schroeder at MIT. |
| 1970s | The C shell (csh) is developed by Bill Joy as a graduate student at University of California, Berkley. It was designed to have simlar syntax to the C language and introduced interactive features like command history and aliases. |
| 1971 | The first Unix shell is developed by Ken Thompson at Bell Labs & modeled on the Multics shell. It introduced a more compact syntax for input/output redirection and the concept of pipes which allowed the output of one command to passed to the input of another. |
| 1977 | Stephen Bourne at Bell Labs created the Bourne shell (sh) as a replacement for the Thompson shell. In addition to being a command interpreter, it also includes features that allow it to be used as a scripting language. The Bourne shell was included with Version 7 Unix which also included the utilities grep (as egrep and fgrep), AWK, & sed. |
| 1983 | The GNU Project is started by Richard Stallman, leading to a proliferation of CLI tools |
| 1989 | Bourne-again shell (Bash) is developed by Brian Fox for the GNU Project as a free alternative to the Bourne shell. Bash goes on to gain widespread adoption and becomes the default shell for many Linux distributions. |

## Sources
1. [Command-line interface](https://en.wikipedia.org/wiki/Command-line_interface#Modern_usage_as_an_operating_system_shell)
1. [Multics](https://en.wikipedia.org/wiki/Multics)
1. [The Origin of the Shell](https://www.multicians.org/shell.html)
1. [Thompson shell](https://en.wikipedia.org/wiki/Thompson_shell)
1. [Bourne shell](https://en.wikipedia.org/wiki/Bourne_shell)
1. [C shell](https://en.wikipedia.org/wiki/C_shell)
1. [Evolution of shells in Linux](https://developer.ibm.com/tutorials/l-linux-shells/)
1. [GNU Project](https://en.wikipedia.org/wiki/GNU_Project)
1. [Bash (unix shell)](https://en.wikipedia.org/wiki/Bourne_shell)
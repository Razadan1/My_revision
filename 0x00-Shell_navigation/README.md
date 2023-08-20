# SHELL & SHELL NAVIGATION
👋Hi there !!!. Welcome to my first ALX project (0x00-Shell, navigation)
In this Repo, I will explain what a shell is, and how we navigate the shell environment.

# What is a shell?
A shell is a tool or a command-line interface that we use in communicating and interacting with the computer operating system by entering commands. It allows us to carry out different tasks, manage files and directories, run programs, and perform system administration tasks. They are also called Terminal.
## Types of Shell
There are different types of shells and they are:
Bash (Bourne Again shell), Zsh (Z shell), Fish (Friendly Interactive shell), Csh (C shell), Tcsh (TENEX C shell), PowerShell, and so on.
- **Bash (Bourne Again Shell)**: Bash is one of the most widely used shells in Unix-like operating systems. It's the default shell on many Linux distributions and macOS. It offers a rich set of features, scripting capabilities, and extensive support in the open-source community.
- **Zsh (Z Shell)**: Zsh is another popular shell that builds upon features from Bash and other shells. It offers advanced tab completion, spelling correction, and customization options, making it a favorite among power users.
- **Fish (Friendly Interactive Shell)**: Fish is designed to be user-friendly and easy to use. It provides color highlighting, intelligent tab completion, and a pleasant user interface.
- **Csh (C Shell)**: Csh was one of the earliest Unix shells and is known for its C-like syntax. It introduced features like command history and aliases. However, it's less commonly used today compared to more modern shells.
- **Tcsh (TENEX C Shell)**: Tcsh is an enhanced version of Csh, offering improved command-line editing, history, and job control. It retains the C-like syntax but adds some useful interactive features.
- **PowerShell**: While not a traditional Unix-like shell, PowerShell is a shell developed by Microsoft for Windows systems. It focuses on automation and system administration tasks. It incorporates object-oriented programming concepts and allows users to interact with the Windows operating system and various services using cmdlets.

There are various producers of shell which are Linux, Unix Terminal, git bash, Windows Cmd (a.k.a command prompt), and so on. They are the host of the shells mentioned above.

# Shell Navigation
Shell navigation is simply the way we play around and interact with the shell. It is how we give commands, assign tasks and carry out activities in the computer's shell.

## Shell Commands
- **pwd (Print Working Directory)**: This command is used to print the present location or directory a user is working on. It prints the path you are working in.
- **ls (List)**: This command is used to list the content of a directory. It lists both the files and folders in the directory
- **ls -a**: It is used to list all the contents in a directory. It lists the hidden and unhidden files in the directory.
- **ls -l**: This lists the contents in a directory with detailed info about each content.
- **cd (Change Directory)**: Allows you to change your current directory.
- **cd**: Change to your home directory.
- **cd directory_name**: This changes to the specified directory.
- **cd ..**: This moves up to the parent directory.
- **cd /**: Change to the root directory.
- **mkdir (Make Directory)**: This creates a new directory.
- **mkdir directory_name**: Creates a new directory with the specified name
- **rmdir (Remove Directory)**: Remove an empty directory.
- **rmdir directory_name**: Removes an empty directory with the specified name.
- **rm (Remove)**: Delete files or directories.
- **rm file_name**: Remove a file.
- **rm -r directory_name**: Remove a directory and its contents recursively.
- **cp (Copy)**: Copy files or directories.
- **cp source destination**: Copy a file or directory from the source to the destination.
- **mv (Move)**: Move files or directories.
- **mv source destination**: Move a file or directory from the source to the destination. It can also be used for renaming.
- **mv oldname newname**: To Rename a file or folder (directory)
- **touch**: Create an empty file.
- **touch file_name**: Creates an empty file with the specified name.
- **ln (Link)**: Create hard or symbolic links to files.
- **ln -s source_link_name destination_link_name**: Create a symbolic link (soft link) from the source to the destination.
- **find**: Search for files and directories in a specified location.
- **find starting_directory -name "filename"**: Searches for files with the specified name within the starting directory and its subdirectories.
- **grep**: Search for specific text within files.
- **grep "search_text" file_name**: Searches for the specified text within the given file.

These are just a few basic commands for shell navigation. Each shell may have its own command, variation, or additional features. Using these commands and techniques, you can easily and effectively navigate and manage the file system within a shell environment.

**Note**: All commands should be in lowercase as the shell is case-sensitive.

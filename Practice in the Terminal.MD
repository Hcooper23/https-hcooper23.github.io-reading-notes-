## Linux Tutorial - 1. The Command Line

- The command line, or terminal, is a text-based interface to the system where commands are entered by typing them on the keyboard and feedback is given as text. It provides a powerful way to interact with the system, allowing for efficient execution of commands and automation of tasks. Commands in the terminal consist of the command itself followed by command line arguments, which can include options to modify the behavior of the command. The opening a terminal can be done through different methods depending on the operating system, such as accessing it through the application's menu or using keyboard shortcuts. These terminals operate in a shell, with Bash (Bourne Again Shell) being the most common shell used in Linux.My big monment was understanding the separation of commands and command line arguments, with options being used to modify command behavior.

- Things I want to know more about:

  - Shell scripting and automation.
  - Exploring different shells available in Linux.
  - Understanding common command line utilities and their usage.

## Linux Tutorial - 2. Navigation

- Throughout this section, we learned about the basics of navigating the Linux system. Here are the key points to summarize what we covered: pwd (Print Working Directory): This command displays the current working directory, providing the absolute path of your location. Ls (List): This command lists the contents of a directory. It can be used with various options and arguments to modify its behavior.
Paths: Paths are used to refer to files or directories in the system. There are two types of paths:
Absolute paths: They start from the root directory ("/") and specify the location in relation to the root. Relative paths: They are specified in relation to the current directory and do not begin with a slash.

Below are examples of Path Buiudling Blocks:

"~" (tilde): Represents the home directory of the current user.
"." (dot): Refers to the current directory.
".." (dot dot): Refers to the parent directory.
cd (Change Directory): This command allows you to change your current directory. Without any arguments, it takes you back to your home directory.

Tab Completion: Tab completion is a useful feature that automatically completes commands or paths when you press the Tab key. It saves time and helps avoid typos.

## Linux Tutorial - 3. More About Files

- Throughout this section, we covered several important concepts related to Linux. Here's a summary of what we discussed: Everything is a File: In Linux, everything, including directories, is considered a file. This understanding helps to manage files and directories efficiently. Linux is an extension-free system: Unlike some other operating systems like Windows, Linux ignores file extensions to determine the file type. Instead, it looks inside the file to identify its format. This means that you can have a file with any extension, and Linux will still treat it based on its actual content.
The file Command: The file command is used to determine the type of a file. By providing the file's path as an argument, you can obtain information about its format. Linux is Case-Sensitive: Linux distinguishes between uppercase and lowercase letters in filenames. Two files or directories with the same name but different cases are considered distinct entities. Spaces in Names,: While spaces are allowed in file and directory names, they require special handling on the command line. To treat a name with spaces as a single argument, you can enclose it in quotes (' ') or use an escape character () before the space. Hidden Files and Directories: Files and directories in Linux can be hidden by prefixing their names with a dot (.), such as .hidden. Hidden files are not listed by default with the ls command, but you can use the -a option (ls -a) to display them. These concepts provide a foundation for understanding how Linux handles files and directories, and they will be useful as you continue to explore and interact with the system.

## Linux Tutorial - 4. Manual Pages

- Manual Pages provide comprehensive information about Linux commands, including their functionality and usage. You can access them using the 'man' command followed by the command you want to look up. The manual pages consist of different sections, including the command's name, description, synopsis, and command line options. To exit the manual pages, press 'q'. You can perform keyword searches within the manual pages using 'man -k' followed by the search term, and search within a specific page by pressing '/' followed by the term. Command line options can be specified using long hand (--) or short hand (-) and can be combined for chaining multiple options together.

## Linux Tutorial - 5. File Manipulation

- In this section, we explored essential file and directory manipulation commands in Linux, such as mkdir for creating directories and organizing files hierarchically. We learned about rmdir for removing empty directories and the touch command for creating blank files and modifying their timestamps. The cp command allows us to make duplicates of files or directories by specifying the destination path, while the mv command is used for moving files or directories, including renaming them. The rm command is used for deleting files, and with the -r option, it can remove directories and their contents recursively. Understanding paths (absolute and relative) and utilizing command line options are key to effectively using these commands. It is crucial to exercise caution as the command line does not provide an undo feature for irreversible actions.
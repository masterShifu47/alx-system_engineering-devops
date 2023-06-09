# 0x00-shell_basics

This repository contains a collection of shell scripts that cover the basics of shell scripting. Each script focuses on a specific task or concept, providing practical examples and explanations.

## Scripts

The project includes the following scripts:

1. **0-current_working_directory**: Prints the absolute path of the current working directory.
2. **1-listit**: Displays the contents of the current directory.
3. **2-bring_me_home**: Changes the working directory to the user's home directory.
4. **3-listfiles**: Displays the contents of the current directory in a long format.
5. **4-listmorefiles**: Displays the contents of the current directory, including hidden files, in a long format.
6. **5-listfilesdigitonly**: Displays the contents of the current directory in a long format, with user and group IDs displayed numerically, and includes hidden files.
7. **6-firstdirectory**: Creates a directory named "my_first_directory" in the /tmp/ directory.
8. **7-movethatfile**: Moves the file named "betty" from /tmp/ to /tmp/my_first_directory/.
9. **8-firstdelete**: Deletes the file named "betty".
10. **9-firstdirdeletion**: Deletes the directory named "my_first_directory" in the /tmp directory.
11. **10-back**: Changes the working directory to the previous one.
12. **11-lists**: Lists files in multiple directories in a long format.
13. **12-file_type**: Prints the type of the file named "iamafile" in the /tmp directory.
14. **13-symbolic_link**: Creates a symbolic link named "__ls__" to the /bin/ls command.
15. **14-copy_html**: Copies HTML files from the current directory and its subdirectories to the parent directory.
16. **100-lets_move**: Moves files beginning with an uppercase letter to the directory /tmp/u.
17. **101-clean_emacs**: Deletes files ending with the "~" character in the current directory.
18. **102-tree**: Creates a tree-like directory structure in the current directory.

## Description

Each script in the project serves a specific purpose and demonstrates different shell scripting concepts. Here is a brief description of what each script does:

- **0-current_working_directory**: This script prints the absolute path of the current working directory using the `pwd` command.
- **1-listit**: It displays the contents of the current directory using the `ls` command.
- **2-bring_me_home**: This script changes the working directory to the user's home directory using the `cd` command.
- **3-listfiles**: It displays the contents of the current directory in a long format using the `ls -l` command.
- **4-listmorefiles**: This script displays the contents of the current directory, including hidden files, in a long format using the `ls -la` command.
- **5-listfilesdigitonly**: It displays the contents of the current directory in a long format, with user and group IDs displayed numerically, and includes hidden files using the `ls -lan` command.
- **6-firstdirectory**: This script creates a directory named "my_first_directory" in the /tmp/ directory using the `mkdir` command.
- **7-movethatfile**: It moves the file named "betty" from /tmp/ to /tmp/my_first_directory/ using the `mv` command.
- **8-firstdelete**: This script deletes the file named "betty" using the `rm` command.
- **9-firstdirdeletion**: It deletes the directory

 named "my_first_directory" in the /tmp directory using the `rmdir` command.
- **10-back**: This script changes the working directory to the previous one using the `cd -` command.
- **11-lists**: It lists files in multiple directories in a long format using the `ls -l` command with directory paths as arguments.
- **12-file_type**: This script prints the type of the file named "iamafile" in the /tmp directory using the `file` command.
- **13-symbolic_link**: It creates a symbolic link named "__ls__" to the /bin/ls command using the `ln -s` command.
- **14-copy_html**: This script copies HTML files from the current directory and its subdirectories to the parent directory using the `cp` command.
- **100-lets_move**: It moves files beginning with an uppercase letter to the directory /tmp/u using the `find` and `mv` commands.
- **101-clean_emacs**: This script deletes files ending with the "~" character in the current directory using the `find` and `rm` commands.
- **102-tree**: It creates a tree-like directory structure in the current directory using the `mkdir` command.

Feel free to explore each script and run them to understand how they work and learn more about shell scripting.

## Usage

To use these scripts, follow these steps:

1. Open a shell environment (e.g., Terminal, Command Prompt).
2. Navigate to the directory where the scripts are located.
3. If necessary, make the script executable using the appropriate command for your operating system.
4. Run the desired script using the appropriate command.

Make sure to read the script descriptions and understand their purpose before running them to avoid any unintended consequences.

## Contributing

Contributions to this project are welcome! If you have any improvements, bug fixes, or additional scripts that you think would be valuable, feel free to submit a pull request. Please ensure that your contributions align with the project's scope and follow best practices.

## License

This project is licensed under the ALX SE License. For more information, refer to the LICENSE file.

---

Feel free to modify this README.md file according to your project's specific requirements and add any additional sections or information that you find necessary.

#Shell Scripting Basics Exercises

#Run `chmod u+x file_name` on the terminal to make the script files executable.

* [0-current_working_directory][1]: Prints the absolute path name of the current working directory.

* [1-listit][2]: Displays the contents list of the current directory.

* [2-bring_me_home][3]: Changes the working directory to the user's home directory.

* [3-listfiles][4]: Displays the current directory contents in a long format.

* [4-listmorefiles][5]: Displays the current directory contents in the long format, including hidden files.

* [5-listfilesdigitonly][6]: Displays the current directory contents in long format, with user and group IDs displayed numerically, and includes hidden files.

* [6-firstdirectory][7]: Creates a directory named `my_first_directory` in the `/tmp/` directory.

* [7-movethatfile][8]: Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory`.

* [8-firstdelete][9]: Deletes the file `betty`.

* [9-firstdirdeletion][10]: Deletes the directory `my_first_directory` that is in the `/tmp` directory.

* [10-back][11]: Changes the working directory to the previous one.

* [11-lists][12]: Lists all files, including hidden files, in the current directory and the parent of the working directory and the `/boot` directory (in this order), in long format.

* [12-file_type][13]: Prints the type of the file named `iamafile`. The file `iamafile` is in the `/tmp` directory.

* [13-symbolic_link][14]: Creates a symbolic link to `/bin/ls`, named `__ls__` in the current directory.

* [14-copy_html][15]: Copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. We consider that all HTML files have the extension `.html`.

* [100-lets_move][16]: Moves all files beginning with an uppercase letter to the directory `/tmp/u`.

* [101-clean_emacs][17]: Deletes all files in the current working directory that end with the character `~`.

* [102-tree][18]: Creates the directories `welcome/`, `welcome/to/` and `welcome/to/school` in the current directory using one combined command.

* [103-commas][19]: Lists all the files and directories of the current directory, separated by commas (`,`). Directory names end with a slash (`/`). Files and directories starting with a dot (`.`) are listed. The listing is alpha ordered, except for the directories `.` and `..` which are listed at the very beginning. Only digits and letters are used to sort; Digits come first. The listing ends with a new line.

* [school.mgc][20]: To be used with the command `file` to detect `School` data files. `School` data files always contain the string `SCHOOL` at offset 0.

#Run the command `file -C -m school.mgc` on the terminal to produce the compiled magic file. 

[1]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/0-current_working_directory
[2]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/1-listit
[3]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/2-bring_me_home
[4]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/3-listfiles
[5]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/4-listmorefiles
[6]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/5-listfilesdigitonly
[7]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/6-firstdirectory
[8]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/7-movethatfile
[9]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/8-firstdelete
[10]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/9-firstdirdeletion
[11]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/10-back
[12]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/11-lists
[13]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/12-file_type
[14]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/13-symbolic_link
[15]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/14-copy_html
[16]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/100-lets_move
[17]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/101-clean_emacs
[18]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/102-tree
[19]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/103-commas
[20]: https://github.com/KEvans254/alx-system_engineering-devops/blob/master/0x00-shell_basics/school.mgc

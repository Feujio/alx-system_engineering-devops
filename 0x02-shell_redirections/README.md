# 0x01 Shell, I/O Rediction

In this project, I will explore a powerful feature used by command line programs called _input/output redirection_.


## What each scripts do?

* 0-hello_world: prints "Hello, World", followed by a new line to the standard output
* 1-confused_smiley:  displays aconfused smiley "(Ôo)'
* 2-hellofile: displays the content of the `/etc/passwd` file
* 3-twofiles: displays the content `etc/passwd` and `/etc/hosts`
* 4-lastlines: displays the last 10 lines of `etc/passwd` to the display
* 5-firstlines: displays the first 10 lines of `/etc/passwd` to the display 
* 6-third_line: displays the third line of the file `iacta`
* 7-file:  creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` ending by a new line
* 8-cwd_state: writes into the file `ls_cwd_content` the result of the command `ls -la`. If the file `ls_cwd_content` already exists, it should be overwritten. If the file `ls_cwd_content` does not exist, create it.
* 9-duplicate_last_line: Duplicate the last line of the file `iacta`
* 10-no-_more_js: deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory and all its subdirectories
* 11-directories: counts the number of directories and sub-directories in the current directory.

  1 The current and parent directories should not be taken into account
  2 Hidden directories should be counted
* 12-newest_files: create a script that displays the 10 newest files in the current directory. Requirements:

  1 One file per line
  2 Sorted from the newest to the oldest
* 13-unique: takes a list of words as input and prints only words that appear exactly once.

  1 Input format: One line, one word
  2 Output format: One line, one word
  3 Words should be sorted
* 14-findthatword: display lines containing the pattern `root` from the file `/etc/passwd`
* 15-countthatword: display the number of lines with an occurence of the pattern `bin` in the file `/etc/passwd`
* 16-whatsnext: display lines containing the pattern `root` and 3 lines after them in the file `/etc/passwd`
* 17-hidethisword: displays all the lines in the file `/etc/passwd` that do not contain the pattern "bin"
* 18-letteronly: displays all lines of the file `etc/shh/sshd_config` starting with a letter
* 19-AZ: repace all caharcters `A` and `c` from input to `Z` and `e` respectively
* 20-hiago: removes all letters `c` and `C` from input
* 21-reverse: reverse its input

## License
None.

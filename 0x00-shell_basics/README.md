# 0x00 Shell, basics
> A Project from ALX SE program to learn about __bash__.
<div align="left">


  <p align="left">
    <a href="https://github.com/Feujio/alx-system_engineering-devops">View Demo</a>
    ·
    <a href="https://github.com/Feujio/alx-system_engineering-devops/issues">Report Bug</a>
    ·
    <a href="https://github.com/Feujio/alx-system_engineering-devops/issues">Request Feature</a>
  </p>
</div>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

## About The Project

### Context

Performing repetitive tasks with the mouse is no longer for a grown up like up. As a software engineer in the making, I must become computer literate.

Welcome to this journey!

### Built With

* [Markdown](https://www.markdownguide.org/)
* [Bash](https://www.gnu.org/software/bash/)

### Prerequisites

* git ([_or follow click on this link (download page of Git) if your OS is not Debian/Ubuntu_](https://git-scm.com/downloads))

  ```sh
  apt-get install git
  ```

### Installation
1. Clone the repo

   ```sh
   git clone https://github.com/Feujio/alx-system_engineering-devops.git
   ```
## Task 0: Where am I?

### The problem

Print the absolute path name of the current working directory. In order words, I should provide a script to display where I stand in the __hierarchical directory stucture__. This position should include all the steps to find where I stand.

### Concepts

* Script: a file that the system can execute. It is written in a scripting language: bash, python, ...
* Absolute path name: a type of path that begins with / character
* current working directory: where I stand in the hierarchical directory structure

### pseudocode & Flowchart

> print the path I stand in the file system process

[Flowchart for pwd](https://drive.google.com/file/d/1t1JxCfoODvp-oLnn9judEA5qeiXz7uy1/view?usp=sharing)

## Task 1: What's in there?

### The problem

Display the contents list of your current directory. In order words, I should provide a script to display all the files ans directories within my current working directory.

### Concepts

* Directory: collection of files and directories. It can be empty.

### pseudocode & Flowchart

> Begin
> 1. print all the files and directories within my current working directory.
> End

## Task 2: There is no place like home

### The problem

Change the working directory to the user's home directory. In order words, from where I stand in the hierarchical directory structure, I shoud go to the directory represented by the deading slash /.

### Concepts

* Root directory: the specific directory that is represented by the leading slash.

### pseudocode & Flowchart

> Begin
> 1. Go to directory with pathname /
> End

## Task 3: The long format

### The problem

Display current directory contents in a long format. In order words, display current directory contents with the following components: 
* access rights to the file, 
* the number of hards links, 
* the file's owner username,
* the name of the group that owns the file,
* Date and time of the file's last modification,
* name of the file.

### Concepts

* long format content of a file

### pseudocode & Flowchart

> Begin
> 1. display all the cited components of the file's content.
> End

## Task 4: Hidden files

### The problem

Display current directory contents, including hidden files (starting with .). Use the long format.

### Concepts

* Hidden files: files with name that starts with .

### pseudocode & Flowchart

> Begin
> 1. display all the current directory contents, including hidden files
> End

## Task 5. I love numbers

### The problem

Display current directory contents:
* in Long format
* with user and group IDs displayed numerically
* and hidden files (starting with .)
* the name of the group that owns the file,
* Date and time of the file's last modification,
* name of the file.

### Concepts

* No new concepts

### pseudocode & Flowchart

> Begin
> 1. display all the cited components of the file's content.
> End

## Task 6: Welcome

### The problem

Create a script that creates a directory named *my_first_directory* in the */tmp/* directory

## Task 7: Betty in my first commit

### the problem

Move the file `betty` from `/tmp/` to `/tmp/my_first_directory`

## Task 8: Bye bye Betty

### The problem

Delete the file `betty` that is in `/tmp/my_first_directory`

## Task 9: Bye bye my first directory

### Problem

Dete the directory `my_first_directory` that is in `/tmp/`

## Task 10: Back to the future

### Problem

Change the working directory to the previous one

## Task 11. Lists

### The problem

Display all the contents (even the hidden files) in long format of the following directories:
* current directory
* the parent of the working directory
* `/boot` directory

## Task 12. File type

### Problem

Prints the type of a file.

## Task 13. We are symbols, and inhabit symbols

### Problem

Create a symbolic link (in the current working directory) to `/bin/ls` named `__ls__`.

### Concepts

* Symbolic link: reference a file name by multiple names.

## task 14. Copy HTML files

### Problem

Crate a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directorry or were newer than the versions in the parent of the working directory.

## Task 15: Let's move

### Problem

Move all files beginning with an uppercase letter to the directory `/tmp/u`

## Task 16: Clean Emacs

### Problem

Delete all files in the current working directory that end with the character `~`
## Task 17: Tree

### Problem

Create 3 directories with one command

## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork it (<https://github.com/Feujio/alx-system_engineering-devops/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

## License

No license.


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
### Technical Writing

* [Othneil Drew,
 for his great README template I modified](https://github.com/othneildrew/Best-README-Template/blob/master/BLANK_README.md)
* [Dan Bader, for his great README template I modified](https://github.com/dbader/readme-template/blob/master/README.md)


<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/Feujio/alx-system_engineering-devops.svg?style=for-the-badge
[contributors-url]: https://github.com/Feujio/alx-system_engineering-devops/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Feujio/alx-system_engineering-devops.svg?style=for-the-badge
[forks-url]: https://github.com/Feujio/alx-system_engineering-devops/network/members
[stars-shield]: https://img.shields.io/github/stars/Feujio/alx-system_engineering-devops.svg?style=for-the-badge
[stars-url]: https://github.com/Feujio/alx-system_engineering-devops/stargazers
[issues-shield]: https://img.shields.io/github/issues/Feujio/alx-system_engineering-devops.svg?style=for-the-badge
[issues-url]: https://github.com/Feujio/alx-system_engineering-devops/issues
[license-shield]: https://img.shields.io/github/license/Feujio/alx-system_engineering-devops.svg?style=for-the-badge
[license-url]: https://github.com/Feujio/alx-system_engineering-devops/blob/master/LICENSE.txt


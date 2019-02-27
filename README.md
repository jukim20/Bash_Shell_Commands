# Terminal Commands for the Unix Shell
Mac OS Bash Shell Commands

## Working with Directories
| Key/Command | Description |
| ----------- | ----------- |
| . | current directory |
| .. | parent directory |
| cd [folder] | move to the directory (ex. cd Desktop) |
| cd | move to home directory |
| cd ~ | move to home directory
| cd .. | move to parent directory |
| ls | list of contents in the current directory |
| ls -a | list w/ hidden contents |
| ls -l | long form with more info |
| ls .. | list of contents in parent directory |
| pwd | show working directory |
| mkdir [dir] | make new directory |
| cp -r [dir] / [new directory] | copy directory into new directory |
| rm -r [dir] | remove directory and all sub directories |
| find . -type [type] | lists the given type (ex. find . -type d => only the directories) |
| find . -name [file] | lists the file that contains the name (ex. find . -name *.txt => returns all text files) |
| chmod [user][group][other] | give precise permission |


## Working with Files
| Key/Command | Description |
| ----------- | ----------- |
| touch [file] | create new file |
| cp [file] [new file] | copy file into new file |
| cp [file] [dir] | copy file into directory |
| rm [file] | remove file |
| rm -i [file] | ask before removing file |
| ? | applies to files missing one character (ex. cp morsec?.txt backup => copies morsecp.txt into backup folder) |
| * | applies to any number of characters (ex. cp *.txt backup => copies all txt files into backup folder) |
| mv [file] [new file] | Move / rename |
| wc [file] | print word count of the file |
| wc -l [file] | print number of lines in the file |
| head -n [n] [file] | print first n number of lines of the file |
| tail -n [n] [file] | print last n number of lines of the file |
| cat [file] | concatenate to screen |
| [command] > [file] |  push output to file |
| [command] >> [file] | append output to file (ex. wc -l *.pdb >> length.txt => doubles the length file) |
| [command] < [file] | read content from file |
| sort [file] | sort content of file according to alphabetical order |
| sort -n [file] | sort content of file according to numerical order |
| sort -r [file] | sort in reverse order |
| grep [str] [file] | find and return lines containing string in the file |
| grep -w [str] [file] | find and return lines containing the whole word str |
| grep -n [str] [file] | find the number of times the string has appeared |


## Piping Commands
| Key/Command | Description |
| ----------- | ----------- |
| [command-a] \| [command-b] |  run command a, pass result to command b, run command b (ex. sort length.txt | head -n 5 => sort the file and prints first 5 lines)


## Working with Nano
| Key/Command | Description |
| ----------- | ----------- |
| nano [file].txt | creates a new text file |
| ^ | control |
| ^O | save file |
| ^X | exit file |


## Command history
| Key/Command | Description |
| ----------- | ----------- |
| history | shows all past commands |
| !! | execute the last command |


## Help
| Key/Command | Description |
| ----------- | ----------- |
| [command] --help | offers help (ex. cp --help) |
| man [command] | shows manual for command (exit with q) |


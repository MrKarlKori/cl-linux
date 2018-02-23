# Cheatsheet

### Усталяванне праграмных пакетаў
1. sudo apt-get install <name> - install package
2. sudo apt-get update - update list of new versions of packages
3. sudo apt-get upgrade - real update packages to newer version
4. sudo apt-get remove <name> - remove package
5. sudo apt-get remove --purge <name>
6. sudo apt-get clean - delete used .deb files
7. apt-cache show <name> - info about package
8. apt-cache search <name> - search

### Праца з тэкстам
1. cat <filename> - show content of file
2. head <filename> - show first 10 lines of text
3. tail <filename> - show last 10 lines of text
4. tail -f <filename> - show last 10 lines of text and watch changing
5. grep '<substr>' <filename> - show all lines, including <substr> of file
6. less <filename> - open file in pager mode
7. diff <file1> <file2> - comparison 2 files line-by-line
8. wc <filename> - count of lines (-l), words (-w), symbols (-m) in file
9. echo <text> - return entered text
10. <command> > <filename> - output result of command in file
11. <command> >> <filename> - append result of command in file
12. <command> &> / &>> <filename> - error message overwrite / append to file
13. <command> < <filename> - input content of file in command
14. <commandA> | <commandB> - send result of commandA in commandB

### Іншыя карысныя каманды
1. reset - reload terminal
2. clear - remove all text from terminal
3. exit - exit from shell
4. man <command-name> - open manual for this command
5. history - history commands in session
6. ! - execute command under code in history
7. !! - last command
8. &_ - enter argument from last command
9. tab - autofilling of command
10. alias - list of aliases for command, existing in system
11. alias <name>='<contentcommand>' - create new alias
12. Ctrl-C - interrupt of accomplishing command
13. Ctrl-Z - interrupt command at time, with command fg command will accomplish again
14. Ctrl-Shift-V - enter copyied text to terminal
15. Ctrl-Shift-C - copy text from terminal
16. fallocate -l <size> <filename> - create a file with particular size
17. uname -a - full information about system
18. top - watching current processes
19. ifconfig - network interfaces

curl, wget, df, mtr, ssh.. and so on!

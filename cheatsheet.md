# Cheatsheet

## Усталяванне праграмных пакетаў
sudo apt-get install <name> - install package
sudo apt-get update - update list of new versions of packages
sudo apt-get upgrade - real update packages to newer version
sudo apt-get remove <name> - remove package
sudo apt-get remove --purge <name>
sudo apt-get clean - delete used .deb files
apt-cache show <name> - info about package
apt-cache search <name> - search

## Праца з тэкстам
cat <filename> - show content of file
head <filename> - show first 10 lines of text
tail <filename> - show last 10 lines of text
tail -f <filename> - show last 10 lines of text and watch changing
grep '<substr>' <filename> - show all lines, including <substr> of file
less <filename> - open file in pager mode
diff <file1> <file2> - comparison 2 files line-by-line
wc <filename> - count of lines (-l), words (-w), symbols (-m) in file
echo <text> - return entered text
<command> > <filename> - output result of command in file
<command> >> <filename> - append result of command in file
<command> &> / &>> <filename> - error message overwrite / append to file
<command> < <filename> - input content of file in command
<commandA> | <commandB> - send result of commandA in commandB

## Іншыя карысныя каманды
reset - reload terminal
clear - remove all text from terminal
exit - exit from shell
man <command-name> - open manual for this command
history - history commands in session
!<code> - execute command under code in history
!! - last command
&_ - enter argument from last command
tab - autofilling of command
alias - list of aliases for command, existing in system
alias <name>='<contentcommand>' - create new alias
Ctrl-C - interrupt of accomplishing command
Ctrl-Z - interrupt command at time, with command fg command will accomplish again
Ctrl-Shift-V - enter copyied text to terminal
Ctrl-Shift-C - copy text from terminal
fallocate -l <size> <filename> - create a file with particular size
uname -a - full information about system
top - watching current processes
ifconfig - network interfaces

curl, wget, df, mtr, ssh.. and so on!

# SHELL BASICS

In this proyect you learn some abaut Shell

| Comand | What do this |
| ------------- | ------------- |
| pwd  | Prints the absolute path name of the current working directory |
| ls  | Display the contents list of your current directory |
| cd | Changes the working directory to the user’s home directory |
| ls -l | Display current directory contents in a long format |
| ls -la | Display current directory contents, including hidden files |
| ls -lan | Display current directory contents in long format, with user and group IDs displayed numerically and hidden files |
| mkdir | Create a directory |
| mv | Move files |
| rm | Remove files |
| rmdir | Remove Directory |
| cd - | Changes the working directory to the previous one |
| ls -al . .. /boot | List all files of current directory and the parent of the working directory and the /boot |
| file | Prints the type of the file |
| ln | Create a symbolic |
| cp | Copy files |

If you try execute all files in this proyect you can see what do this do, and a correct output of all files

# Outputs

### pwd 

<pre><code>$ ./0-current_working_directory
/0x00-shell_basics
$</code></pre>

### ls

<pre><code>$ ./1-listit
Applications    Documents   Dropbox Movies Pictures
Desktop Downloads   Library Music Public
$</code></pre>

### cd

<pre><code> julien@ubuntu:/tmp$ pwd
/tmp
julien@ubuntu:/tmp$ echo $HOME
/home/julien
julien@ubuntu:/tmp$ source ./2-bring_me_home
julien@ubuntu:~$ pwd
/home/julien
julien@ubuntu:~$ </code></pre>

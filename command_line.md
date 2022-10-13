
# Terminal / git bash / (command line)

### List directory

UNIX: List directory ```ls``` is useful for finding out contents of the current directory:

- ```ls``` tai ```ls -l```

Windows: equivalent command on Windows (command prompt tool) is ```dir```:

- ```dir```

This will give you a list of all folders and files in the current directory:

```
-rw-r--r--  1 mikanokelainen  staff   0  4 Mar 15:40 cmd_terminal_git_pip_venv.md
-rw-r--r--  1 mikanokelainen  staff  21  4 Mar 15:36 hello_world.py
-rwxr-xr-x  1 mikanokelainen  staff  76  4 Mar 15:36 hello_world.sh
```

### Change directory

Change directory ```cd``` is used when we want to navigate to a new location in the folder structure:

- ```cd testdirectory``` means we want to go to a directory names testdirectory
- ```cd testdirectory/testdirectory2``` will move as straight to testdirectory2
- ```cd .. ``` moves us one step "up" in the structure
- ```cd ../..``` moves us two steps up in the structure
- ```cd ~``` moves us to the root


### Make directory

You can create a new directory with ```mkdir```:

- ```mkdir testdirectory``` creates a directory called testdirectory

### Creating a new file

UNIX:

- ```touch test.py```creates an empty file called test.py

Windows:

- ```echo some-text  > filename.txt```

### Moving and copying files

You can move ```mv ```  or copy ```cp ```  a file to a new location:

- ```mv <current path> <new path>``` 
- (windows ```move ```)

- ```cp <current path> <new path>```
- (windows ```copy```) 

### Renaming a file

You can rename a file with the move commad ```mv ```. I.e. by moving the file to same location with different name:

- ```mv <path/current_name> <path/new_name>``` 
- (windows ```move ```)


### Editing files

Nano and Vim are super simple (simple, not easy) text editors you can start up from the command line.

- ```nano test.py``` 

- ```vim test.py``` 

IF YOU END UP IN VIM YOU CAN EXIT WITH ```:q``` :D

For windows you need to install these separately. ``` choco install vim``` should work at least.
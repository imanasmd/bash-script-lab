# 1.pwd(Print name of current/working directory)

When working in a Linux environment, it is essential to understand the **absolute path** of directories within the file system. 
To determine the exact current directory location, the `pwd` (print name of current/working directory) command is used.

```bash
Input:-
user@hostname:~$ pwd and Press the Enter key
```

```bash
Output:-
/home/username or Current location as per your location in linux file subsystem
```

# 2.cd(Change Directory)

The `cd` (change directory) command is used to navigate between directories in a Linux file system. 
It allows users to move to a specified directory using either absolute or relative paths.


a).A double dot (`..`) represents the parent directory (one level up).

Let's assume we are in "/home/alice/Download/music" directry/folder.
```bash
    user@hostname:~/home/alice/Download/music$
```

If we need to get back to alice directory,then we need to write below cmd on terminal
```bash
   user@hostname:~/home/alice/Download/music$ cd ../..
```

After running the above command on terminal,suddenly shell prompt get changed to
```bash
   user@hostname:~/home/alice$
```

If you want to do vice-versa,then we can type command in below style:-
```bash
	user@hostname:~/home/alice$ cd Download/musice
```

b). A single dot (`.`) represents the current directory in the file system.

Refer to current directory
```bash
   ls .
```

Executes script located in current folder
```bash
   ./script.sh
```

Copy file to a folder inside current directory
```bash
    cp file.txt ./backup/
```


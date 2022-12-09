## Set up `bash_profile`
The bash profile contains global options.  Here we will set up some shortcuts to save on typing.  


#### Access `bash_profile`
This file is located in your home directory.  
To access it, use any editor of your choice.
```
$ emacs ~/.bash_profile
```

#### Add these options

```bash
alias home="cd /Users/reshamashaikh"
alias ds8="cd /Users/reshamashaikh/_ds/metis/metisgh/nyc16_ds8"
alias c='clear'
alias rm='rm -i'

alias ls='ls -lGgo'
alias server="python -m SimpleHTTPServer"
```

---

#### Alias shortcut example for project folder
Adding shortcuts save you lots of typing and time
```bash
reshama 🐘  $ pwd
/Users/reshamashaikh
reshama 🐘  $ ds8
reshama 🐘  $ pwd
/Users/reshamashaikh/_ds/metis/metisgh/nyc16_ds8
```

#### Alias shortcut example for home directory
If I want to go back to my home directory, I can type the alias `home` that I added to my `~/.bash_profile` file  
```bash
reshama 🐘  $ pwd
/Users/reshamashaikh/_ds/metis/metisgh/pygotham-2016
reshama 🐘  $ home
reshama 🐘  $ pwd
/Users/reshamashaikh
reshama 🐘  $ 
```

---

#### Removing (or deleting) a file 
Adding `alias rm='rm -i'` to your `bash_profile` includes an added check when deleting a file.   
```bash
reshama 🐘  $ ls *test*
-rw-r--r--  1   0 Jul  5 19:02 testfile.md
reshama 🐘  $ rm testfile.md
remove testfile.md? y
```
Confirming that the file has been deleted  
```bash
reshama 🐘  $ ls *test*
ls: *test*: No such file or directory
reshama 🐘  $ 
```

---

#### Alias for clearing the terminal 

```bash
reshama 🐘  $ c
-bash: c: command not found
reshama 🐘  $ emacs ~/.bash_profile
reshama 🐘  $ source ~/.bash_profile
reshama 🐘  $ c
```
Typing `c` now clears my console (terminal)  
```
reshama 🐘  $ 
```

---

#### Alias for listing files 
This is default file listing
```bash
reshama 🐘  $ ls
README.md		bash_emoji.md		grep_tutorial
bash_commands.md	bash_profile_setup.md	markdown.md
reshama 🐘  $ 
```
This is file listing with option `ls -Glp`:  
```bash
reshama 🐘  $ pwd
/Users/reshamashaikh/_ds/metis/metisgh/pygotham-2016
reshama 🐘  $ ls
total 40
-rw-r--r--   1   1725 Jul  5 19:02 README.md
-rw-r--r--   1    144 Jul  5 19:02 bash_commands.md
-rw-r--r--   1    818 Jul  5 19:02 bash_emoji.md
-rw-r--r--   1    705 Jul  5 19:02 bash_profile_setup.md
drwxr-xr-x  12    408 Jul  5 19:02 grep_tutorial
-rw-r--r--   1   3623 Jul  5 19:02 markdown.md
reshama 🐘  $ 
```

---

### References

[Nate Landau's post: My Mac OSX Bash Profile](https://natelandau.com/my-mac-osx-bash_profile/)

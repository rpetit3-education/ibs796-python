During this course you will have to play with some basic Unix commands. Below are a list of Unix commands you are expected to become comfortable with. You are highly encouraged to further explore Unix, as there are some super useful commands that are outside the context of this course.

You are strongly encouraged to further investigate the optional parameters of each of these commands!

# What is Unix?
First let's clarify what Unix is and why its so cool! Unix is a (and I'm paraphrasing from the [Wikipedia entry](https://en.wikipedia.org/wiki/Unix)) multi-user multi-tasking operating systems. It was originally developed by Bell Labs in 1970. Fast forward a few decades, it is the basis for Apple's OS X and the many flavors of [Linux](https://en.wikipedia.org/wiki/Comparison_of_Linux_distributions). Even Microsoft has begun to implement it into their latest Windows 10 versions via [Windows Subsystem for Linux](https://en.wikipedia.org/wiki/Windows_Subsystem_for_Linux).

## `cat`
The `cat` command allows you to concatenate and print files. For more information see the [Wikipedia Entry](https://en.wikipedia.org/wiki/Cat_(Unix))

#### Example Usage
```
cat somefile.txt
cat file-001.txt file-002.txt ... file-XYZ.txt
```


## `cd`
Good luck avoiding `cd`! The `cd` command allows you to change the working directory, thus navigate between directories. For more information see the [Wikipedia Entry](https://en.wikipedia.org/wiki/Cd_(command))

#### Example Usage
```
cd a_directory/

# ~/ points to your home directory
cd ~/data_analysis/
```


## `chmod`
The `chmod` command allows you to change the file modes/attributes/permissions. For example is allows you to determing who can read or write to one of your files. For more information see the [Wikipedia Entry](https://en.wikipedia.org/wiki/Chmod)

#### Example Usage
```
# Make potential examples!
# Make a file readable and executable by everyone
chmod 755 my-python-script.py
```


## `cp`
The `cp` command allows you to copy files. For more information see the [Wikipedia Entry](https://en.wikipedia.org/wiki/Cp_(Unix))

#### Example Usage
```
cp FILE NEW_FILE

cp my-large-text-file.txt my-second-large-text-file.txt
```


## `head`
Sometimes you don't need to read all of a file. The `head` command will print only the first part of files. For more information see the [Wikipedia Entry](https://en.wikipedia.org/wiki/Head_(Unix))

#### Example Usage
```
# View first 10 lines of a file
head my-large-file.txt

# View first line of a file
head -n 1 my-file.txt
```


## `ls`
Another command which is hard to avoid is the `ls` command. `ls` is used to list the contents of a directory. For more information see the [Wikipedia Entry](https://en.wikipedia.org/wiki/Ls)

#### Example Usage
```
ls

# View contents of your home directory
ls ~/
```


## `man`
When you are stuck, the `man` command can display system documentation for a given command. For more information see the [Wikipedia Entry](https://en.wikipedia.org/wiki/Man_page)

#### Example Usage
```
man THE_COMMAND_OF_INTEREST
man ls 
man man
man rm
man head
```


## `mkdir`
The `mkdir` command allows you to make directories. For more information see the [Wikipedia Entry](https://en.wikipedia.org/wiki/Mkdir)

#### Example Usage
```
mkdir my-new-directory

# Make all sub-directories as well
mkdir -p sub-dir01/sub-dir02/my-new-directory
```


## `mv`
The `mv` command allows you to move files between directories. You can also use the `mv` command to rename files. For more information see the [Wikipedia Entry](https://en.wikipedia.org/wiki/Mv)

#### Example Usage
```
# Move a file to your home directory
mv my-file.txt ~/

# Move a file to your home directory and renome it
mv my-file.txt ~/my-new-file.txt
```


## `pwd`
Sometimee you need to know which directory you are currently in. The `pwd` command does exactly that. It will print your working directory. For more information see the [Wikipedia Entry](https://en.wikipedia.org/wiki/Pwd)

#### Example Usage
```
# Really not much to it!
pwd
```


## `rm`
Probably one the most unforgiven commands in Unix. The `rm` command allows you to remove (or delete) a file from the system. It is unforgiven in the sense of there are no take backs. For more information see the [Wikipedia Entry](https://en.wikipedia.org/wiki/Rm_(Unix))

#### Example Usage
```
rm my-file.txt

# Remove a directory with contents
rm -rf my-directory/
```


## `tail`
Similar to `head`, the `tail` command does the exact opposite by displaying only the last part of a file. For more information see the [Wikipedia Entry](https://en.wikipedia.org/wiki/Tail_(Unix))

#### Example Usage
```
# View last 10 lines of a file
tail my-large-file.txt

# View last line of a file
tail -n 1 my-file.txt
```


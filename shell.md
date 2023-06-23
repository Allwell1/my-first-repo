# Shell Commands

## Listing
- `ls` - list: for listing the content of a dir
```sh
$ ls 
``` 
- `ls` *`dirname`* - for listing the content of any dir by providing the dir name

```sh
$ ls .. Desktop/
```
- `ls ..` - is used for viewing or listing the content of the previous dir 
```sh
$ ls ..
```

## Navigating
before we can navigate, we need to know the current working dir. to check that we `pwd` which means `print working dir`

```sh
$ pwd
c:/users/user
```
in navigating the current dir `.` while the previous dir is `..` and the command for navigating is `cd` which means `change dir`.

```sh
$ cd ..
$ cd my-dir/
```
## Creating Dir
The command for creating a dir is `mkdir` which means `make directory`
### Usage
it is used by adding the name of the directory you want to create after the `mkdir` command

```sh
$ mkdir document
$ mkdir html
```
## Creating Files
To create a file, we have various command for that. But the command for creating an empty file is `touch` command
```sh
$ touch file.docx
$ touch index.html
``` 

## Deleting a Dir
- Deleting an empty dir
________
Command fot deleting an empty dir is `rmdir`
### Usage
add the name of the dir you want to delete after the command `rmdir`
```sh
$ rmdir html
```
>NB: If html dir is empty, the deletion will not work.

- Deleting a non empty dir
________
The command for removing a dir and all it's content `rm -rf`. This command will remove every dir and file present recusively.
>NB: This command when used wrongly can not recover anything.
```sh
$ rm -rf html
```





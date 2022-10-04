# OpenSource Lecture Note 4

```sh
1. pwd : shows the current path in a hierarchical directory
2. cd : change directory
3. ls : list files and directories
```

- cd and ls arguments

```sh
 1. / : root
 2. . : current directory
 3. ~ : home of current user
 4. /[directory name] : absolute path
 5. ./[directory name] : relative path
 6. ../[directory name] : relative path
```

- cd and ls options

```sh
 1. -l : show detailed information(long format)
 2. -lh : same as above, but size in units
```

---

- I am currently using iterm and want to see the files in my Woowoo directory.  
  ls /Woowoo didn't work Here ls Woowoo/ works!!!

---

# Important contents

- cp : copy files and directories

```sh
1. cp file1 file2
2. cp -i file1 file2
3. cp file1 dir1
4. cp -R dir1 dir2
```

- mv : move files and directories or rename them

```sh
 1. mv file1 file2
 2. mv -i file1 file2
 3. mv file1 file2 dir1
 4. dir1 dir2
```

- rm : delete files and directories **permantely and irreversevely**

```sh
 1. rm file1 file2
 2. rm -i file1 file2
 3. rm -r dir1 dir2
```

- mkdir : make a new directory

---

# Questions

![long format](https://miro.medium.com/max/1400/0*rLVhxj6mUY_GEH9c.png)
In the picture above, the professor said that you need to know how to distinguish between a file and a folder in the file permission section, and I am curious how to do that.

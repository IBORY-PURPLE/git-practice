# OpenSourceSW Lecture Note 5

- standard output

```sh
1. > : You have arrived as a new text file from the file in your current location.
ex) ls -lh > file.txt 이렇게 사용!
2. >> : It is used as above, but if there are modifications, it feels like a new save rather than overwriting it.
```

- standard input

```sh
1. < :< Write the input to the previous command after it. In short, the command < filename
ex) sort < words.txt > sorted_words.txt   Use like this!
```

- pipeline

```sh
1. | : Allows you to use commands in succession.
ex) command1 | command2 | command3 이렇게 사용해서 command1의 outputd을 command2의 input으로 사용한다.
```

- Expansion

```sh
1. echo : The string after echo is output as it is.
2. echo * : Used similarly to ls, it shows the subfiles and folders of the current directory.
3. echo ~ : Shows the best folder. I am /user/mac.
```

- Backslash

1. \ : Allows you to use commands written on one line across multiple lines.

---

- Permissions

![permission](https://i0.wp.com/techbyexample.com/wp-content/uploads/2022/04/file-permissions.drawio-min.png?w=640&ssl=1.png).

1.(-) 2.(rwx) 3.(rwx) 4.(rwx) r=read, w=write, x=execute

1. file type.
2. read, write, execute permissions for the file owner.
3. for the group users.
4. for all other users.

- "chmod" changes permissions

ex) chmod 600 some_file.
In the 600 part, for each digit, it means to give authority to the 2, 3, and 4 above.

```sh
chmod values
1. 0 = - - -
2. 1 = - - x
3. 2 = - w -
4. 3 = - w x
5. 4 = r - -
6. 5 = r - x
7. 6 = r w -
8. 7 = r w x
```

---

- text editors

```sh
1. vi, vim(고수)
2. nano(초보자)
3. gedit(초보자)

```

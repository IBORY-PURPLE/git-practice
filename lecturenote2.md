# OpenSourceSW Lecture Note2

* standard output
```sh
1. > : 현재 디렉토리에 있는 파일들을 새로운 text파일로 저장할 때 사용
ex) ls -lh > file.txt 이렇게 사용!
2. >> : 위에 처럼 사용이 되는데 이놈은 수정사항이 있으면 덮어서 저장이 아니라 새롭게 저장하는 느낌
```

* standard input
1. < : 뒤에 입력으로 들어갈 파일을 적는다
ex) sort < words.txt > sorted_words.txt 이렇게 사용!

* pipeline 
1. | : 명령어를 연달아 사용할 수 있게 한다.
ex) command1 | command2 | command3 이렇게 사용해서 command1의 outputd을 command2의 input으로 사용한다.

* Expansion
```sh
1. echo : echo뒤의 문자열을 그대로 출력한다
2. echo * : ls와 비슷하게 사용되어 지금 위치한 directory의 하위 파일,폴더를 보여준다.
3. echo ~ : 최상의 폴더를 보여준다. 나는 /user/mac이다

* Backslash
1. \ : 한 line에 쓸 명령어들을 여러줄에 걸쳐 사용할 수 있게 해준다.
ex) ls -l \
    > --reverse \
    > --human-readable 

---
* Permissions
![permission](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQKgZsXq241Ay_aCFqPToUXkGGcIBJptu8RCA&usqp=CAU)

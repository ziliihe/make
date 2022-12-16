# make

[特殊符号](https://www.gnu.org/software/make/manual/html_node/Automatic-Variables.html#Automatic-Variables)

[ref](https://stackoverflow.com/questions/3220277/what-do-the-makefile-symbols-and-mean)

`all: library.cpp main.cpp`

- `$@` evaluates to `all` [target will be generated]
- `$<` evaluates to `library.cpp` [first source file]
- `$^` evaluates to `library.cpp main.cpp` [all source file]

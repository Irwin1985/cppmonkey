# CPP Monkey:
This is my implementation of the monkey programming language following 
the wonderful book <a href="https://interpreterbook.com" target="_blank">Writing An Interpreter In Go</a>. You should definetly grab a copy if you still struggle with `Operator Precedence Parsing`. Catch2 is being used for tests.

### Try it:
The code is self contained as a dockerized app.

Build & Jump inside the container:

```
$ docker build -t cppmonkey .
$ docker run -it --rm -v "$PWD":/usr/project cppmonkey
```

Run the test
```
$ ./entrypoint.sh ftest
```

Run the REPL
```
$ ./entrypoint.sh frun
```

### Note:
The primary `raison d'être` of this repo is to learn compilers and C++. Please help review my c++ code, suggest improvement, best practices and idoms.

### Online C++ Docs:
- https://www.learncpp.com/
- http://www.trytoprogram.com/c-programming
- http://www.fredosaurus.com/notes-cpp/index.html

phpbf
=====

PHPBF is a Brainf*ck compiler/interpreter, written in PHP.
It can compile your Brainf*ck code to C, or you can run the code in the built-in interpreter.

Note: This version has only been tested with PHP version 5.5.1

Examples of Use
---------------

Compiling
```
./phpbf compile examples/test.bf test.c
clang examples/test.c -o test
./test
```

Interpreting
```
./phpbf run examples/hello.bf
```

What the f*ck is Brainf*ck?
---------------------------
[Wikipedia Article On Brainf*ck](http://en.wikipedia.org/wiki/Brainf*ck)

[Muppet Labs Resource](http://www.muppetlabs.com/~breadbox/bf/)

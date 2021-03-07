# Learning C++

## Here I am going to use this repo as my C++ language brushup/practice/recall after long days

### Installation

I don't do that much step for installation, as I already have by default in both linux and mac machine

```Shell
$ g++ --version
```
It will show some version along with the path, which means it is installed and ready to go. If you get any other error please check with google for instructions.

### Execute a program
Since C++ is the compiler based program, we have to compile the code before execute it. Once we compiled the source code, the compiler will generate the binary file with respect to the source code. 

#### For Compile:
```Shell
$ g++ -o outFileName codeFileName
```
1) g++ - which denotes its C++ language. 
2) -o denotes - that we need out file to execute the program.
3) outFileName - Enter the name that you want as output (app name), along with path if you need by default it will use current path. 
4) codeFileName - name of your C++ file which you like to compile 

example:
```Shell
$ g++ -o app helloWorld.cpp
```
#### Run:
```Shell
$ ./app 
```
./ denotes the current path and output binary file name to run the application   

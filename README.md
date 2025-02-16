# [WIP] Base C/C++ project
A starting point for C and C++ projects.

It includes a basic main.cpp file and the needed Makefiles for being
able to build the project, that may have multiple files in multiple dirs.

You should only touch the Project.mk to set the needed options to build your
project. Leave alone the Functions.mk and the Makefile unless you know what
are you doing.

If your project needs any deps (apart of installed libs), you can put
the headers and implementations in the 'deps' folder.

The idea is to use a script to build all the deps.



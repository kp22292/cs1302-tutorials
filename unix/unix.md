# Unix Tutorial

![Status: Not Ready](https://img.shields.io/badge/Status-Not%20Ready-red.svg)

## Introduction

Unix is a family of computer operating systems that derive from work performed
in the 1970s at the Bell Labs research center by Ken Thompson, Dennis Ritchie, 
and others. In this course, we use the term Unix to refer to systems that are
Unix-like, i.e., their user interface and basic set of utilities are 
reminiscent of a Unix system. 

In Unix, the primary end-user, text-based interface to the system is a program 
called the _shell_. This program can be usually be accessed via a 
_terminal emulator_ if a graphical windowing system is available or directly
otherwise. In the shell, you enter _commands_ at a _prompt_. Here is an
example of what such a prompt might look like:

```
bash$
```

The shell is just another way to interact with computer. These days, all
students are familiar with the point-and-click graphica windowing systems
provided in operating systems like Windows, macOS, and even phones.
However, only some realize that the windowing system they're used to is
only one way to interact with a computer. 

## Files and Directories

When working in a shell, you are always working in some _directory_, which
is just another word for folder. The directory that you are in is commonly
referred to as your _current working directory_ or _present working directory_.
In fact, the second term provides you a hint for a command that can be used
to see where you are:

```
bash$ pwd
/home/users/mary
```

As seen above, the `pwd` command can be used to print out your present
working directory. In this case, this directory is called `mary` and
the _absolute path_ to `mary` is `/home/users/mary`. An abolsute path
just tells us the sequence of directories that need to be traversed
if we wanted to reach a file from the root of the filesystem. 



## Useful Commands

## Input/Output Redirection and Pipes

## Getting Help

## Manual Pages

### Understanding the Synopsis

When inspecting a manual page for a program, we're often concerned with what command-line
options can be used to customize the behavior of the program. One of the first sections
that will appear in a manual page is the `SYNOPSIS`, and it details this information.
Here is an example for the `ls` command:

```
ls [OPTION]... [FILE]...
```

This is enough information to infer that when a user executes the `ls` command, they 
can include:
* zero or more options (`OPTION`); and
* zero or more files (`FILE`).

Consider `[OPTION]...`, the square brackets (`[`, `]`) let us know that providing
a value for `OPTION` is not required, and the `...` let us know that more than
one `OPTION` can be provided.

Here is the general form:

```
utility_name [-a] [-b] [-c option_argument]
    [-d|-e] [-f[option_argument]] [operand...]
```

More detailed information about how to interpret a synopsis can be found in
[POSIX.1-2017 12.1 Utility Argument Syntax](https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/V1_chap12.html#tag_12_01).

<hr/>

## References

<hr/>

[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-nc-nd/4.0/)

<small>
Copyright &copy; Michael E. Cotterell, Bradley J. Barnes, and the University of Georgia.
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a> to students and the public.
The content and opinions expressed on this Web page do not necessarily reflect the views of nor are they endorsed by the University of Georgia or the University System of Georgia.
</small>
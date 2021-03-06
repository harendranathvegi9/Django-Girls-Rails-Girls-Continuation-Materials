# Python

Python is one of the many programming languages that are used to write programs. They can be used for desktop applications, meaning programs that operate locally (operate on your own computer) or they can be used for programs that run on a server and are part of a website. It is a good idea to start with Python or Ruby as a beginning because they are relatively simple in syntax and quite general purpose. There are two versions of Python that are used a lot: Python 2 and Python 3. Python 3 is the newer version but only about 30% of the Python software is written in it. Most of the Python software is written in Python 2 so that is why some of the resources are in Python 2, some are in Python 3 because as with the software, not all tutorials have updated their syntax on Python 3. This is going to be a slow, gradual process. 

We will speak about the Python interpreter a bit. There are two types of languages: those that are compiles and those that are interpreted. It all goes down to how the program is turned into a machine language. In Python there is a middle-man: the Python interpreter that is the first "person" who reads your program. 

## Useful Resources: 

**Note:** Some of the resources are on Python 2 and some are on Python 3. Here is what to have in mind: 

1. You run a command in the command line in python 3 by using python3 name_of_the_file.py. 

2. You should put parenthesis on the print method, meaning print("string"). In Python 2 you can just use print "string"

3. When you ask for keyboard input, in Python 3 you use input, whereas in Python 2 you use raw_input. 

**Another note:** Some of the resources ask you to write your Python programs in a separate file in your text editor and run it by using the command-line. Some of the resources use the Python interpreter to demonstrate the result of some lines of code. The first approach should be somewhat familiar because so far, we have created all our HTML and other files like that. When you are doing serious programming in future, you will be using this approach. If you are just interested in the result of a function, expression, etc. you use the Python interpreter. You start it by typing python in the command line. What happens is that you start the Python interpreter and when you type a line of code and press Enter, it gives you the outcome of the line of code on the next line. If you type 3 + 5, it will return 8. So when you see some code that starts with >> it is in the interpreter, so start Python in your command line. To get out of the interpreter and back to your normal command line, press Control and C at the same time. 

**If you have a problem with some exercise, check whether you use the correct syntax for the version you are using.**


***
 

Python installation: [Django Girls Tutorial](https://tutorial.djangogirls.org/en/python_installation/)

Printing text to the screen: [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/ex1.html)

Indentation: [Python for you and me](http://pymbook.readthedocs.io/en/py3/thebeginning.html#whitespaces-and-indentation)

Comments: [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/ex2.html)

Numbers and math: [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/ex3.html)

Numerical types: [Tutorial Point, Python](https://www.tutorialspoint.com/python/python_numbers.htm): up until the Mathematical Functions section 

Variables and strings: [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/ex4.html), again [Learn Python the Hard Way](https://learnpythonthehardway.org/book/ex5.html) and again [Learn Python the Hard Way](https://learnpythonthehardway.org/book/ex7.html)

Escape characters: [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/ex9.html) & [Learn Python the Hard Way](https://learnpythonthehardway.org/book/ex10.html) 

Reading input from the keyboard: [Python for You and Me](http://pymbook.readthedocs.io/en/py3/variablesanddatatypes.html#reading-input-from-the-keyboard)

Argument variables: [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/ex13.html) & [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/ex14.html)

Reading from a file: [Python for You and Me](http://pymbook.readthedocs.io/en/latest/file.html): until the Count spaces section & [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/ex16.html) & [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/ex17.html): if you have problems understanding the process of manipulating files, have in mind that we first need to make a file handle, which is an object that is like a DVD player and writer, which is "the device" which allows you to write and read on the file. As the DVD is unreadable unless you have a DVD player so is the file without file handler. That is why we created a variable target in ex 16.

Functions: [Python Guide on swaroopch.com](https://python.swaroopch.com/functions.html): until he VarArgs Section & [Learn Python the Hard Way](https://learnpythonthehardway.org/book/ex18.html) & again [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/ex19.html): if you want, try ex20 as well, it is a bit more difficult so you can ask the mentors in the study group

Functions returning something: [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/ex21.html)

**Time for review!!! Hurray**: go back to every single exercise you did and do it again. It is going to take you about a week to review. If yo finish faster, here are some additional resources: 

[Codecademy](https://www.codecademy.com/learn/python): Python Syntax and String Sections

[Learn Python the Hard Way](https://learnpythonthehardway.org/book/): every exercise, including those that we missed until ex26 and take the quiz. If yo get something wrong, it is fine. Programming has lot to do with finding your mistakes because even the most experienced programmers make mistakes and spend lots of time to find them. 

Basic syntax: [Tutorials Point](https://www.tutorialspoint.com/python/python_basic_syntax.htm)

Table of arithmetic operators: [Tutorials Point](https://www.tutorialspoint.com/python/python_basic_operators.htm): just the first one 

Comments, Python interpreter, indentation: [Python for You and Me](http://pymbook.readthedocs.io/en/py3/thebeginning.html#): here they also speak about modules at the end, but you have enough knowledge to understand it

Learn more about strings and what you can do with them: [Python for You and Me](http://pymbook.readthedocs.io/en/py3/strings.html): until the Palindrome checking section

If you are interested about some history and characteristics of Python: [Python Tutorial Point](https://www.tutorialspoint.com/python/python_overview.htm): until Python Features

***
So now we can continue with more Python: 

Logic and boolean operators: [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/ex27.html) & [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/ex28.html): in ex27, if you find difficulties, try to say to your self *In order the whole statement to be true, both this and this whould be true* for and. *In order the whole statement to be true, either this or this should be true* and you will not make mistakes. In ex28, use your interptreter to check whether you got the answers right: you start it by typing python to the command line. [Python for You and Me](http://pymbook.readthedocs.io/en/py3/operatorsexpressions.html#logical-operators): short section but with interesting content. 

If, elif, else: [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/): ex29, 30 & 31 & [A Byte of Python](https://python.swaroopch.com/control_flow.html): until the While section; [Python for You and Me](http://pymbook.readthedocs.io/en/py3/ifelse.html)

**Review Time:** 

[Codecademy](https://www.codecademy.com/learn/python): Conditionals and Control Flow Sections

***

Lists: [Python for You and Me](http://pymbook.readthedocs.io/en/py3/looping.html#lists): Just the section on lists, [Tutorials Point](https://www.tutorialspoint.com/python/python_lists.htm): until the Indexes and Matrix Section;  

For-loops: [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/ex32.html)

Tuples: [Tutorials Point](https://www.tutorialaspoint.com/python/python_tuples.htm)

While-loops: [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/ex33.html), [Python for You and Me](http://pymbook.readthedocs.io/en/py3/looping.html#while-loop): until Power Series & [Python for You and Me](http://pymbook.readthedocs.io/en/py3/looping.html#range-function): the Range and the Continue Statement Sections

**Review Time:**

Lists, while, for and exercises: [Learn Python the Hard Way](https://learnpythonthehardway.org/python3/): ex34 to 38 including. 

Loops, Functions and Lists: [Codecademy](https://www.codecademy.com/learn/python): sections 7 and 8 (without Looping over a Dictionary)

***

Dictionaries: links to be added


***
##Excercises:

Simpler exercise: [Hacker rank](https://www.hackerrank.com/domains/python/py-introduction)

Nice source because you use the command-line and do it like a real programmer: [Exercism.io](http://exercism.io/languages/python/about)




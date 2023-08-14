## Choosing your own print() Ending
Let's say you're writing a full paragraph and don't need a newline character after every sentence. print() can accommodate that through its optional end parameter. Try modifying your print() statements as follows:

# lib/app.py
print("Hello world!", end=" ")
print("Hello sun!", end="!! ")
print("Hello sky!", end="!!!\n")
What do you see when you execute lib/app.py from the command line with these new end strings?

 python lib/app.py
 ```js
Hello world! Hello sun!!! Hello sky!!!!
```
end can be a string of any length, including characters like the newline \n.


## Exploring Python with the Python Interpreter

Using the Python shell is a great way to quickly test out some
code, or check your syntax, without needing to run an entire application.

type `python3` in terminal.

Python 3.10.12 (main, Jun 11 2023, 05:26:28) [GCC 11.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> print("hello python shell")
hello python shell
>>> first_number = 7
>>> print(first_number)
7
>>>  to esc we press `ctl+d`

## To run npm test

1. sudo apt install pipenv 

2. pip install --upgrade pipenv

3. pipenv --python 3.10.12 install

4. pipenv shell

5. pytest. 
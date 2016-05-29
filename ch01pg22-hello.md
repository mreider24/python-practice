# Chapter 01 page 22 - hello.py

First little program in the book.  It is a simple hello world / simple input program.  Asks for name and age and prints it back.  No semicolons at the end like in JS.  Also didn't like it when I tried to concatenate the string and number in lines 10 and 11 like you can in JS.  Will see if there is a different way to do that.



```python
print('Hello World')
print('What is your name?')  # ask for their name
myName = input()
print('It is good to meet you, ' + myName)
print('The length of your name is: ')
print(len(myName))
print('What is your age?')  #ask for their age
myAge = input()
print('You will be ' + str(int(myAge) + 1) + ' in a year.')
```

** Stupid edit number one.  There is a different way to concatenate strings and numbers.  I used it here in the last line without realizing it.  Using str() changes the integer into a string so you can complete the sentence as a string.  Talked about it immediately after this exercise in the book.

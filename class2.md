# Class 2
##  _Modules and Testing_
# 
#### First of all, the TDD stands for Test-Driven Development. It's like a technique used meanwhile writing the code and for testing causes before implemention. It has benifits such as easiness of reading and speed of execution. It splits work into small requirements and refactors the tools of TDD.
#
#### if __name__ == "__main__" is like an  idiom, it allows to execute code when the file runs as a script, but not when it’s imported as a module.

#### Script: When run as a script, your code prompts the user for input, calls echo(), and prints the result.By implementing the if __name__ == "__main__" idiom in your code, you set up an additional entry point that allows you to use echo() right from the command line. if it's true; then the indented code following the conditional statement executes, if false; Python skips the indented code.
#
#### Every recursive function must have a base condition that stops the recursion or else the function calls itself infinitely. The Python interpreter limits the depths of recursion to help avoid infinite recursions, resulting in stack overflows. Recursion makes the code clean, and complex tasks can be broken down into sub-problems.
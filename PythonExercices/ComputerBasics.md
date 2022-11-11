# Computer basics

A computer, or more precisly, a CPU is like calculator.

All it can do, is do stuff to numbers :

- add, substract them,
- Multiply them,
- etc

More generaly, computers change numbers, which are called information.

These are the Bits or 1's and 0's.

And they change these numbers one step at a time.

This can be illustrated by a code block:


```
# In a python file, every step
Step = 1

# is executed sequencially
Step = 2

#ending when there are no more steps
print(Step + 1)

````
Result, the screen prints : 3

This concept is easy to grasp, \
But if a computer doesn't print, or output, what you think it should output, \
This means you made a logical mistake

Take this example :

```
# If I say :
Step = 1

# And then say 
If Step + 1 == 3: 

  # when I was only at step 2 then it will not print what I want
  print("this is what I want")

# Instead, it will print something different
else:
  print("somehting I don't want")

```

This is an obvious example, but it is a basic "logical" misfunction \
The computer always does the correct thing, but the way I formulated what I wanted it to do was logically incorrect.

This is, in my opinion, the first fact a computer programmer must come to terms with. \
And sadly, or interestingly, this is not easy.

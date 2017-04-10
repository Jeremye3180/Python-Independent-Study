## What's New?

Hello everyone, here I am once again, talking to you every now and then. I
am back to tell you guys that I have started to work on these mini projects
to play around with python, to see what I can create in python.


I will say that if you ever are sitting down in front of your computer, you are bored learning syntax
and you have no idea how to make something from scratch without some form of prompt, use google.
I was absolutely clueless on what to make, so I searched for some mini projects for python and
boom, found a website that lists 5 different python activities from easiest to hardest.

I would also tell you to take your time making these projects because of a couple of reasons.
Taking your time on these projects allows more creative licensing and makes you feel proud of completing even
the most basic of achievements. Take a look at my code for task 2 vs task 3 and you can see that
while I completed the requirements for both, my overall presentation of task 3 is presentable but
there is not much creativity put into its content.

At the time of this blog, I have only achieved the first 3, but I will continue to finish the other two by
next week.

Without further ado, let's dive into projects!


## What did I make?


My first task was to create a program that simulates rolling a dice.
dd 

```python

import random

def dice():
  print (random.randint(1,6))
  
  

dice()
```

So, the amount of code makes this task look simple right? I would agree with you
but the particular cream of the crop is understanding import and randint.
Python has many commands built into it's own language, but there are some like random that are not,
so we use import to tell python "Hey we need this command to be available for our code!"
randint on the other hand is an add on to random that specifically tells python to make a random
integer to appear so the computer can print an actual numerical value.

Now, task 2 is an expansion of task 1 so it will be a bit more than a few lines of code.



```python
import random

cpu = random.randint(1,6)#makes computer to pick a number from 1-6
user = int(input("Pick a number between 1-6!:"))#Asks user to choice from 1-6

def guess():
 
  print ("The computer picked", cpu)#shows computer's answer
  
#Will print a hint to how far off the user's choice was or if they were right.  
if user == cpu: 
  print("You guessed it!")
elif user > cpu:
  print ("Your number was too high!")
elif user < cpu:
  print ("Your number was too low!")
 
  
guess()#runs method
```

My task was to make a guessing game where the computer picks a value from 1-6
and the user has to pick the matching value. This means that the user has to interact with
the program for it to function so python has a command called ```input()``` which allows the user to respond
to whatever is within it. In this case, I used it to ask the user for a value but I ran into
a problem where the user enters a number, but it could not be compared. Now this sort of thing occurred
in my experience with ruby as well so to explain what happened here, the user types in a number
but python treats it as a string while the cpu creates a value("3" vs 3). To fix this problem
in this case, I had to encase the input function for the user's response with ```int``` which converted
the string into an integer.


Task 3


This task was different from the others, it was to create a mad libs style program that asked
the user for things such as nouns, adjectives, and verbs which would then be combined together into
a sentence or paragraph.



```python

def Madlib():
  
  Name1 = input("Give me a name:")
  Place = input("How bout a place:")
  Adj = input("How are they feeling:")

  print (Name1 + " went to the " + Place + " because" + Name1 + " felt so " + Adj + " today.")
  

Madlib()
```

This project to me felt more of a concept of me understanding how to concatenate strings and
variables to make a full coherent sentence. By adding "+" signs in between variables and strings, you can combine them into one sentence.






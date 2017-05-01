# Hello all you Lovely People!


 This week, I spent time learning about arrays and for loops in python compared to that of Ruby or Javascript!
 I made a project that will make the user a sandwich based on their inputs!
 
 
 
 ## The code:
 
 
 ```python
 
 
Sandwich = []


def food():
 
  talk = input("Cheese, Pbj, or Ham sandwich?")
 
  Sandwich.append(talk)
 

def order():

  for pref in Sandwich:
 
    if pref == "Cheese":
      ch = input("Do you want cheddar, American or Swiss cheese?")
      cook = input("Grilled or Regular?")
      print("You got a " + cook  + " " +  pref + " sandwich with " + ch + " inside!")
      break
 
    elif pref == "Pbj":
      print("Its Peanut Butter Jelly Time!!!")
      break
    
    elif pref == "ham":
      print("You got a " + pref + "sandwich")
      
food()
      
    
order()
 
 ```
 
 
 There are many key elements here to focus on so I will try to break everything down as best as I can.
 Firstly, you will notice that an array in python is pretty much the same as it is in javascript or ruby, but
you can also see that I have a line of code that appends as well. This line of code will take the user's input and add it into the
empty array.

The for loop is quite interesting because it reads whatever is in the array and will interpret it as such. This means
that whenever the user enters one of the three types of sandwiches, it will enter the array to be analyzed by the for loop.

From here, the majority of the code is a mixture of if statements and concatenation but there is one thing that is very interesting that I learned...

# Takeaways

I learned that it is possible to call a variable within a print command that is in an if statement. I came across a problem where setting a variable to an input
will always ask the user to answer it and I only found out the problem when I was able to insert the variable definition within in the particular if statement.

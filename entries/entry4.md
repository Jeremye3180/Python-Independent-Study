

# Greetings


Hello everyone, this week I decided to create a project where I could show off the syntax of 
mathematics in python while also learned more about converting the user's input into something
more flexible. This project is essentially a giant calculator that can do many different actions
for the user. 


# What can it do?

Examine the project below:
 
 ```python
 
value = int(input("what number?")) 
sign = input("Do you want to(press 1-5): 1.add,2.subtract,3.multiply,4.divide,5. Power") 
value_2 = int(input("By what number?"))

def calc():
 
    
  if sign == "1":
    print(value + value_2)
        
  elif sign == "2": 
    print(value - value_2)
    
  elif sign == "3": 
    print(value * value_2)
  
  elif sign == "4": 
    print(value / value_2)
    
  elif sign == "5":
    print(value ** value_2)
    
calc()
 ```
 
 This calculator will take 2 numbers from the user and then perform an operation to get a
 final answer in the end. If the user picks a number from 1 to 5 on the second question, 
 they can add, subtract, multiply, divide, or raise their number to a power of the second number
 they enter. This project could come in use when I need to complete my math homework and can be used 
 in the professional field for things such as accounting. 
 
 
# Takeaways


 For the longest time, the code above was not making any progress. I tried rearranging my code,
changing my code, and even restarting the entire project, yet I still received an error on my terminal 
which said the process exited with code: 0. Upon further research, I found that this line is not actually an error,
but a message that my terminal tells me that my code is running properly. However, if a number other than 0 appeared,
then the code has a problem. So what was wrong with my code, if that was not an error, then why was
nothing printing to the console? I am still confused about this even at the time of writing this
blog but after my access to repl.it was restored, the code worked perfectly on that website instead of my terminal.


 Also, I have learned that there are other websites that I can use to test my code if others are down
 for a period of time which means that I can continue to work on my code without massive interference.

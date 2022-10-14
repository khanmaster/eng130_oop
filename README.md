# Python Object Oriented Programming
## 4 Pillars of OOP
### methods/functions 
#### Modules
##### Lib - Packages

#### use case - benefits - examples of builtin modules - packages
```python
# Lucky draw
# key word called import
# import random
#from random import *
#import math

#print(random)

#print(random.random())
#print(random())

# each time it's run it generates a rondom number - 0-1

# calculate DOB or year of birth

from random import *
import math
import datetime, sys
import os
# print(os.cpu_count()) #  this will result in number cpu based your OS
# print(datetime.date.today())
# #print(datetime.date)
# # This will result today's date based on your OS
# print(sys.path)


#


#
# number = 23.66
# # any numbers - to round the figure up -
# # number 1.50 above to round up 2
# # number 1.49 or less round down to 1
# print(math.ceil(number)) # ceil will round the figure up
# print(math.floor(number)) # floor will help you round the figure to bottom

# Don't Repeat Yourself (DRY)
# reusable - saves time - saves money
# Let's build some functions
# it's part of your exam
# syntax def name(): - def name() - daf name(): - def name:
# first iteration
# def greeting():
#     # greet the user
#     print("Hello Dear ")
#
#     #pass
#     # keyword called pass
# # # unless the function is called it does nothing
# # greeting()
#
# # greet the user with their name
# def greet_user(name): # create a function that takes an arg - the name
#     print("Hello Dear " + name) # adding 2 string with user input()
#     #pass
# greet_user("Sparta")
# let's create a function that take int as an args
# def add(value1, value2): # take user input as int the add them together display the outcome
#     print("this function is to provide addition functionality ")
# # return statement
#     return value1 + value2
# # if you are using a return statement and calling the function - it needs to be in a print st.
# print(add(2, 2))
#
#

# Cinema example
#age = 15

# if age >= 18:
#     print("You are the correct age to watch this film and can buy a ticket")
# elif age < 18:
#     print("I'm afraid you are not the correct age to watch this film")

# film ratings

# film rating
#


















film_rating = input("enter age please ")
def movie_rating(age):
    if film_rating.lower() == "universal":
        print("all age groups can watch this film")
    elif film_rating.lower() == "pg":
        print("General viewing, but some scenes may be unsuitable for young children.")
    elif film_rating.lower() == "12" or film_rating == "12a":
        print("Films classified 12A and video works classified 12 contain material that is not generally suitable for children aged under 12. No one younger than 12 may see a 12A film in a cinema unless accompanied by an adult.")
    elif film_rating.lower() == "15":
        print("No one younger than 15 may see a 15 film in a cinema.")
    elif film_rating.lower() == "18":
        print("No one younger than 18 may see an 18 film in a cinema.")
    else:
        print("this is not a correct rating, please use unniversal, pg, 12, 12a, 15, 18")
    return f"Your age is {age}"
print(movie_rating(film_rating))

# refactor all the tasks into OOP - create functions for each - it should provide same functionality
```
#### OOP code along diagram
![](https://github.com/khanmaster/eng130_oop/blob/main/images/OOP_python.png)


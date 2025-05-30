# Exp.No:26  
## Method Overriding



### AIM  
To write a Python program to create a Parent class `Bird` and inherit two child classes `Sparrow` and `Ostrich` from the `Bird` class with the same method `flight()`. Create an object for each class and call the methods of the class which will print the name of the bird that is flying.



### ALGORITHM

1. **Begin the program.**
2. **Define the Bird class**:
   - Create a method `intro()` to print "There are many types of birds."
   - Create a method `flight()` to print "Most of the birds can fly but some cannot."
3. **Define the Sparrow class**, which inherits from `Bird`:
   - Override the `flight()` method.
   - Call the `intro()` method from the parent class.
   - Print "Sparrows can fly."
4. **Define the Ostrich class**, which inherits from `Bird`:
   - Override the `flight()` method.
   - Call the `intro()` method from the parent class.
   - Print "Ostriches cannot fly."
5. **Create an object `obj_bird`** of the `Bird` class.
6. **Create an object `obj_spr`** of the `Sparrow` class.
7. **Create an object `obj_ost`** of the `Ostrich` class.
8. **Print the general message** "There are many types of birds."
9. **Call the `flight()` method** on each object (`obj_bird`, `obj_spr`, `obj_ost`) to display the respective messages.
10. **Terminate the program.**



### PROGRAM

```
class Bird:
    def intro(self):
        print("There are many types of birds.")
	
    def flight(self):
        print("Most of the birds can fly but some cannot.")

class sparrow(Bird):
    def flight(self):
    
        print("There are many types of birds.\nSparrows can fly.")
	
class ostrich(Bird):
    def flight(self):
        print("There are many types of birds.\nOstriches cannot fly.")
       
	
obj = Bird()
obj.intro()
obj.flight()
obj = sparrow()
obj.flight()
obj = ostrich()
obj.flight()


```

### OUTPUT
![image](https://github.com/user-attachments/assets/03b8733b-495a-4047-a4b8-c517a59ac1c6)


### RESULT
Thus the Python program to create a Parent class `Bird` and inherit two child classes `Sparrow` and `Ostrich` from the `Bird` class with the same method `flight()`has been successfully executed.

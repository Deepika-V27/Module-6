# Exp.No:29  
## Encapsulation



### AIM  
To write a Python program to create a class `Student` with the private members `name` and `age`, and add getter and setter methods to initialize and modify the `age` variable.



### ALGORITHM

1. **Start the Program.**
2. **Define the `Student` class.**
   - Inside the `Student` class, define the `__init__` method to initialize `name` and the private member `__age`.
3. **Define a getter method** `get_age` to return the value of the private member `__age`.
4. **Define a setter method** `set_age` to set a new value to the private member `__age`.
5. **Create an object `stud`** of the `Student` class with the name 'Jessa' and age 14.
6. **Print the name and the age** of `stud` using the getter method.
7. **Use the setter method** `set_age` to change the age of `stud` to 16.
8. **Print the name and the updated age** of `stud` using the getter method.
9. **End the program.**



### PROGRAM

```
class Student:
    def __init__(self, name, age):
        self.__name = name  # private member
        self.__age = age    # private member
    
    # Getter method for age
    def get_age(self):
        return self.__age
    
    # Setter method for age
    def set_age(self, age):
        if age > 0:  # simple validation
            self.__age = age
        else:
            print("Age must be a positive number")
    
    # Getter method for name (optional)
    def get_name(self):
        return self.__name
    
    # Display student information
    def display(self):
        print(f"Student Name: {self.__name}, Age: {self.__age}")


if __name__ == "__main__":
    # Create a student object
    student1 = Student("Alice", 20)
    
    # Display initial values
    student1.display()
    
    # Get age using getter
    print(f"Current age (via getter): {student1.get_age()}")
    
    # Update age using setter
    student1.set_age(21)
    print("After setting new age:")
    student1.display()
    
    # Try to set invalid age
    student1.set_age(-5)
    
    # The private members cannot be accessed directly
    # This would raise an AttributeError:
    # print(student1.__age)

```

### OUTPUT
![image](https://github.com/user-attachments/assets/6b6526f4-4ef7-45eb-a0f6-9f936214fe25)

### RESULT
Thus the Python program to create a class `Student` with the private members `name` and `age`, and add getter and setter methods to initialize and modify the `age` variable waqs implemented successfully.




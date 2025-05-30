# Exp.No:30  
## COUNTER CLASS


### AIM  
To write a Python program to create a `Counter` class that can increment the value of a counter.



### ALGORITHM

1. **Start the Program.**
2. **Define the `Counter` class.**
   - Initialize the `current` variable with 0.
3. **Define the `increment()` method** to increment the value of `current` by 1.
4. **Define the `value()` method** to return the current value of `current`.
5. **Define the `reset()` method** to reset the `current` value back to 0.
6. **Create a `counter` object** of the `Counter` class.
7. **Call the `increment()` method** three times to increment the counter.
8. **Call the `value()` method** and print the result to show the current counter value.
9. **End the program.**



### PROGRAM

```
n=int(input())
count=0
while(n>0):
    count=count+1
    n=n//10
print("The number of digits in the number are:",count)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/72eb069d-4acc-4762-97cb-bec8a56a46a9)

### RESULT
Thus the Python program to create a `Counter` class that can increment the value of a counter has been executed successfully.

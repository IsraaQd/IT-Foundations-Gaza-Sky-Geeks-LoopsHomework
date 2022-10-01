# IT-Foundations-Gaza-Sky-Geeks-LoopsHomework
Assignment 5: Loops homework


# First:- ***Loops***

## 1_ Display numbers from a list using a loop
Write a program to display only those numbers from a list that satisfy the following conditions
The number must be divisible by five
If the number is greater than 150, then skip it and move to the next number
If the number is greater than 500, then stop the loop
> Given: 
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

> Expected output:
```
75
150
145
```

## 2_ Use else block to display a message “Done” after successful execution of for loop
For example, the following loop will execute without any error.
> Given:
```
for i in range(5):
    print(i)
 ```
> Expected output:
```
0
1
2
3
4
Done!
```
 
## 3_Reverse a given integer number
> Given:
```
76542
```
> Expected output:
```
24567
```
 
 
 
 
 
 
# Second:- ***Dict***
## 1: Convert two lists into a dictionary
Below are the two lists. Write a Python program to convert them into a dictionary in a way that item from list1 is the key and item from list2 is the value
> Given:
```
keys = ['Ten', 'Twenty', 'Thirty']
values = [10, 20, 30]
```
> Expected output:
```
{'Ten': 10, 'Twenty': 20, 'Thirty': 30}
 ```
 
 
## 2: Delete a list of keys from a dictionary
> Given:
```
sample_dict = {
    "name": "Kelly",
    "age": 25,
    "salary": 8000,
    "city": "New york"
}
```
 
> Keys to remove:
```
keys = ["name", "salary"]
```
> Expected output:
```
{'city': 'New york', 'age': 25}
```
 
 
 
 
# Third:- ***Sets***

## 1: Add a list of elements to a set
Given a list, write a program to add all its elements into a given set.
> Given:
```
sample_set = {"Yellow", "Orange", "Black"}
sample_list = ["Blue", "Green", "Red"]
```
> Expected output:
###### Note: Set is unordered.
```
{'Green', 'Yellow', 'Black', 'Orange', 'Red', 'Blue'}
```
 
## 2: Return a new set of identical items from two sets
> Given:
```
set1 = {10, 20, 30, 40, 50}
set2 = {30, 40, 50, 60, 70}
```
> Expected output:
```
{40, 50, 30}
```
 
 
 
# Fourth:- ***Tuples***
## 1: Reverse the tuple
> Given:
```
tuple1 = (10, 20, 30, 40, 50)
```
> Expected output:
```
(50, 40, 30, 20, 10)
```

## 2: Access value 20 from the tuple
The given tuple is a nested tuple. write a Python program to print the value 20.
> Given:
```
tuple1 = ("Orange", [10, 20, 30], (5, 15, 25))
```
> Expected output:
```
20
```
 
## 3: Unpack the tuple into 4 variables
Write a program to unpack the following tuple into four variables and display each variable.
> Given:
```
tuple1 = (10, 20, 30, 40)
```
> Expected output:
```
tuple1 = (10, 20, 30, 40)
> Your code
print(a) # should print 10
print(b) # should print 20
print(c) # should print 30
print(d) # should print 40
```

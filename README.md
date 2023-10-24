# Python Data Analytics Cheat Sheet

This a cheatsheet to include most commonly used functions in Data Analysis with 
Python and other major libraries like Pandas, Sci-kitlearn, Seaborn, etc

For beginnerts, the diagram below shows a basic ogranization of functions and 
their usage in Python.

The diagram has the most commonly used classes such as `String`, `List`. It has also 
common core funcyion such as `enumarate`. 

This readme will split into sections. Each section will have commonly used fucctions
belonging to the Class or Library, and a few examples. Futher documentation is linked
to w3schools for Python and Pandas libs for Pandas.

![Python Class Structure](images/python_classes.jpg)

### List

##### append()
[Official Docs](https://www.w3schools.com/python/ref_list_append.asp)

The append function adds a variable to a list. 

_Example 1_
```
my_list = [1, 2, 3]
my_list.append(4)
print (my_list)
```
_output:_
`[1, 2, 3, 4]`

_Example 2_
```
my_list = ["a", "b", "c"]
my_list.append("d")
print (my_list)
```
_output:_
`["a", "b", "c", "d"]`

### Core

#### enumerate()
[Official Docs](https://www.w3schools.com/python/ref_func_enumerate.asp)

The enumerate function is among then inbuilt functions that adds a counter to an iterable and returns an iterator(turple) in the format `index, element`

_Example 1_
```fruits = ["apple", "banana", "cherry"]
for index, fruit in enumerate(fruits):
    print(index, fruit)
```
_output:_
`0 apple
1 banana
2 cherry`

_Example 2_
Incase you want the counter to start with a different value
```fruits = ["apple", "banana", "cherry"]
for index, fruit in enumerator(fruits, start=1):
    print(index, fruit)
```
_output_

1 apple
2 banana
3 cherry




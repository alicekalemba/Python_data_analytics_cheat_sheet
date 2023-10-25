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

##### join()
[Official Docs](https://www.w3schools.com/python/ref_string_join.asp)

The join function is a string method that returns a string in which the elements of a sequence have been joined by a specified delimiter. Its also called a delimiter string.

_Example 1_
```
words = ["Hello", "world"]
result = ' '.join(words)
print(result)
```
_output:_
`Hello world`

_Example 2_
```
words = ["apple", "banana", "cherry"]
result = ', '.join(words)
print(result)
```
_output:_
`apple, banana, cherry`

_Example 3_
```
lines = ["Line 1", "Line 2", "Line 3"]
result = '\n'.join(lines)
print(result)
```
_output:_
```
Line 1
Line 2
Line 3
```



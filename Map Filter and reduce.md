# Map, Filter and Reduce function


## map
### syntax:

```python
map(function, iterable)
```
The function argument is a function that is applied to each element in the iterable argument. The iterable argument can be a list, tuple, or any other iterable object. 

### example:
```python
# List of numbers
numbers = [1, 2, 3, 4, 5]

# Double each number using the map function
doubled = map(lambda x: x * 2, numbers)

# Print the doubled numbers
print(list(doubled))
```
In the above example,The map function applies the lambda function to each element in the list and returns a new list containing the doubled numbers.

## filter
### syntax:

```python
filter(predicate, iterable)
```


### example:

```python
# List of numbers
numbers = [1, 2, 3, 4, 5]

# Get only the even numbers using the filter function
evens = filter(lambda x: x % 2 == 0, numbers)

# Print the even numbers
print(list(evens))
```
In the above example, the lambda function lambda x: x % 2 == 0 is used to filter the numbers list and return only the even numbers. The filter function applies the lambda function to each element in the list and returns a new list containing only the even numbers.

## reduce
### syntax:
```python
reduce(function, iterable)
```
The function argument is a function that takes in two arguments and returns a single value. The iterable argument is a sequence of elements, such as a list or tuple.



### example:

```python
from functools import reduce

# List of numbers
numbers = [1, 2, 3, 4, 5]

# Calculate the sum of the numbers using the reduce function
sum = reduce(lambda x, y: x + y, numbers)

# Print the sum
print(sum)
```
In the above example, the reduce function applies the lambda function lambda x, y: x + y to the elements in the numbers list. The lambda function adds the two arguments x and y and returns the result. The reduce function applies the lambda function to the first two elements in the list (1 and 2), then applies the function to the result (3) and the next element (3), and so on. The final result is the sum of all the elements in the list, which is 15.



# String formatting in python
### Example
```python
txt = "For only {price:.2f} dollars!"
print(txt.format(price = 49))
```
# f-strings in python
## Example
```python
val = 'Geeks'  
print(f"{val} for {val} is a portal for {val}.")  
name = 'Tushar'  
age = 23  
print(f"Hello, My name is {name} and I'm {age} years old.")  
```
## Output:
```
Geeks for Geeks is a portal for Geeks.
Hello, My name is Tushar and I'm 23 years old.
```
We can use it in a single statement as well.
## Example
```python
print(f"{2 * 30})"  
```
## Output:
```
60
```

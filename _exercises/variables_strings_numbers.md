---
layout: page
title: Variable_strings_numbers
description: This notebook has code about various, strings, numbers, etc!
---

# Variables

greeting = "Hello world!"


```python
print(greeting)
```

    Hello world!



```python
exhaustion_level = "Mega"
```


```python
print(exhaustion_level)
```

    Mega



```python
exhaustion_level = "Not Bad"
```


```python
print(exhaustion_level)
```

    Not Bad


You can reassign variables. Variables cannot contains spaces, should be short but descriptive, can include numbers, letters and underscores. 

# Strings


```python
ex_1 = "This is a string."
print(ex_1)
```

    This is a string.



```python
ex_2 = 'This is also a string'
print(ex_2)
```

    This is also a string



```python
ex_3 = 'I asked the question, "When should I use single quotes."'
print(ex_3)
```

    I asked the question, "When should I use single quotes."


Strings have special methods.


```python
historian = "edward gibbon"
print(historian)
```

    edward gibbon



```python
print(historian.title())
```

    Edward Gibbon


() illustrates that you are calling a method.


```python
novelist = "Becky Chambers"
print(novelist.lower())
```

    becky chambers



```python
"becky" == "becky"
```




    True




```python
"becky" == "Becky"
```




    False




```python
first_name = "ada"
last_name = "lovelace"
```


```python
full_name = first_name + " " + last_name
print(full_name)
```

    ada lovelace



```python
greeting = f" Hello, {first_name} {last_name}"
print(greeting.title())
```

     Hello, Ada Lovelace



```python
#Look up more on F strings.
```


```python
first_name = "Ali"
last_name = "Babeu"
```


```python
print(4*2)
print(5+3)
print(16.0/2.0)
print(9-1)
```

    8
    8
    8.0
    8



```python
#This programs stores a favorite number and prints it
favorite_number = (7)
print(favorite_number)
```

    7


## Whitespace


```python
print("tab")
```

    tab



```python
print("\ttab")
```

    	tab



```python
##backslash is an escape character
```


```python
print("languages: \nGreek\nLatin\nEnglish")
```

    languages: 
    Greek
    Latin
    English



```python
str_rspace = "string           "
print(str_rspace)
```

    string           



```python
print(str_rspace.rstrip())
```

    string



```python
example = str_rspace + "."
print(example)
```

    string           .



```python
example_2 = str_rspace.rstrip() + "."
print(example_2)
```

    string.


## Numbers

### Integers


```python
238 + 4834
```




    5072




```python
num = 45
num + 5
```




    50




```python
type(num)
```




    int




```python
30 / 10
```




    3.0




```python
## When you are dividing in Python it gives you a float
```


```python
f = 30/7
```


```python
f
```




    4.285714285714286




```python
type(f)
```




    float




```python

```

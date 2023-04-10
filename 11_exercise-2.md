# Exercise-2

In this exercise make program by using time module \
and if-else statement \
There is hint for you 

```python
import time

a = time.strftime("%H:%M:%S")
print(a)
```

**Output:** 

```markup
07:08:15
```

**note:** \
output isn't same evrytime and it will probably be US time \
if you run that code in your computer/machine,then it will be your computer/machine time.

## Here is all code about it

```python
import time

a = time.strftime("%H:%M:%S")
print(a)

if ("05:00:00" <= a and a <= "12:00:00"):
  print("Good morning sir")
elif ("12:01:00" <= a and a <= "16:00:00"):
  print("Good after noon sir")
elif ("16:01:00" <= a and a <= "04:59:00"):
  print("Good night sir")
  ```

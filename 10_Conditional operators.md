# if-else Statements
Sometimes the programmer needs to check the evaluation of certain expression(s), whether the expression(s) evaluate to True or False. If the expression evaluates to False, then the program execution follows a different path than it would have if the expression had evaluated to True.

Based on this, the conditional statements are further classified into following types:
- if
- if-else
- if-else-elif
- nested if-else-elif.
## An if……else statement evaluates like this:

### if the expression evaluates True:
Execute the block of code inside if statement. After execution return to the code out of the if……else block.\
### if the expression evaluates False:
Execute the block of code inside else statement. After execution return to the code out of the if……else block.
 ## Example:
```python
applePrice = 210
budget = 200
if (applePrice <= budget):
    print("Alexa, add 1 kg Apples to the cart.")
else:
    print("Alexa, do not add Apples to the cart.")
```
## Output:
```
Alexa, do not add Apples to the cart.
```

# elif Statements
Sometimes, the programmer may want to evaluate more than one condition, this can be done using an elif statement.
### Working of an elif statement
Execute the block of code inside if statement if the initial expression evaluates to True. After execution return to the code out of the if block.

Execute the block of code inside the first elif statement if the expression inside it evaluates True. After execution return to the code out of the if block.

Execute the block of code inside the second elif statement if the expression inside it evaluates True. After execution return to the code out of the if block.\
.\
.\
.\
Execute the block of code inside the nth elif statement if the expression inside it evaluates True. After execution return to the code out of the if block.

Execute the block of code inside else statement if none of the expression evaluates to True. After execution return to the code out of the if block.

## Example:
```python
num = 0
if (num < 0):
    print("Number is negative.")
elif (num == 0):
    print("Number is Zero.")
else:
    print("Number is positive.")
```
## Output:
```
Number is Zero.
```

# Nested if statements
We can use if, if-else, elif statements inside other if statements as well. \
Example:
```python
num = 18
if (num < 0):
    print("Number is negative.")
elif (num > 0):
    if (num <= 10):
        print("Number is between 1-10")
    elif (num > 10 and num <= 20):
        print("Number is between 11-20")
    else:
        print("Number is greater than 20")
else:
    print("Number is zero")
```
Output:
```
Number is between 11-20
```

## My all code about conditional operator

```python
# Conditional operators
# <, >, <=, >=, ==, !=

air = input("what is your name?")
bear = int(input("what is your age?"))
clear = int(input("In which class do your read?"))
dear = input("what is your section?")
print("your name is", air, "\n", "your age is", bear, "\n", "your class is",
      clear, "\n"
      "your section is", dear)
'''mai aik program bnao ga ke agr age 18 se kam hai exam possible / impossible nazar ae
or class se board or school exam nazar ae or section se exam kis loction per hai nazar ae'''

if (bear < 18):
  print("you are  not enable for exam")
elif (bear <= 24):
  print("you are enable for exam")
  if (clear == 6 and dear == "a"):
    print("your exam in school and room number 1")
  elif (clear == 6 and dear == "b"):
    print("your exam in school and \n room number 2")
  elif (clear == 7 and dear == "a"):
    print("your exam in school and \n room number 3")
  elif (clear == 7 and dear == "b"):
    print("your exam in school and \n in rooom nomber 4")
  elif (clear == 8 and dear == "a"):
    print("yor exam in board and \n hall of board")
  elif (clear == 8 and dear == "b"):
    print("your exam in board and \n gallery of board")
  elif (clear == 9 and dear == "a"):
    print("your exam in proffesional board and \n ground of board")
  elif (clear == 9 and dear == "b"):
    print("your exam in proffesional board and \n bagicha number 1 of board")
  elif (clear == 10 and dear == "a"):
    print("your exam in proffessional board and \n bagicha number 2 of board")
  elif (clear == 10 and dear == "b"):
    print("your exam in proffessional board and \n bagicha number 3 of board")
  else:
    print(
      "you input wrong class and section. please input class 6-10 and section a or b"
    )

```

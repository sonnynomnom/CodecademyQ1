# Codecademy Python

##### Python

1. Go With the Flow

```python
def clinic():
    print "You've just entered the clinic!"
    print "Do you take the door on the left or the right?"
    answer = raw_input("Type left or right and hit 'Enter'.").lower()
    if answer == "left" or answer == "l":
        print "This is the Verbal Abuse Room, you heap of parrot droppings!"
    elif answer == "right" or answer == "r":
        print "Of course this is the Argument Room, I've told you that already!"
    else:
        print "You didn't pick left or right! Try again."
        clinic()

clinic()
```

2. Compare Closely!

Comparators: `==`, `!=`, `<`, `<=`, `>`, `>=`

```python
# Assign True or False as appropriate on the lines below!

# Set this to True if 17 < 328 or to False if it is not.
bool_one = True   # We did this one for you!

# Set this to True if 100 == (2 * 50) or to False otherwise.
bool_two = True

# Set this to True if 19 <= 19 or to False if it is not.
bool_three = True

# Set this to True if -22 >= -18 or to False if it is not.
bool_four = False

# Set this to True if 99 != (98 + 1) or to False otherwise.
bool_five = False
```

3. Compare... Closelier!
```python
# Assign True or False as appropriate on the lines below!

# (20 - 10) > 15
bool_one = False    # We did this one for you!

# (10 + 17) == 3**16
# Remember that ** can be read as 'to the power of'. 3**16 is about 43 million.
bool_two = False

# 1**2 <= -1
bool_three = False

# 40 * 4 >= -4
bool_four = True

# 100 != 10**2
bool_five = False
```

4. How the Tables Have Turned
```python
# Create comparative statements as appropriate on the lines below!

# Make me true!
bool_one = 3 < 5  # We already did this one for you!

# Make me false!
bool_two = 3 > 5

# Make me true!
bool_three = 8 == 8

# Make me false!
bool_four = 8 < 7

# Make me true!
bool_five = 8 != 7
```

5. To Be and/or Not to Be

- `and`, `or`, `not`

```python
"""
     Boolean Operators
------------------------      
True and True is True
True and False is False
False and True is False
False and False is False

True or True is True
True or False is True
False or True is True
False or False is False

Not True is False
Not False is True

"""
```

6. And

```python
bool_one = False and False

bool_two = False and True

bool_three = True and False

bool_four = True and True

bool_five = True and True
```

7. Or

```python
bool_one = 2**3 == 108 % 100 or 'Cleese' == 'King Arthur'

bool_two = True or False

bool_three = 100**0.5 >= 50 or False

bool_four = True or True

bool_five = 1**100 == 100**1 or 3 * 2 * 1 != 3 + 2 + 1
```

8. Not

```python
bool_one = not True

bool_two = not 3**4 < 4**3

bool_three = not 10 % 3 <= 10 % 2

bool_four = not 3**2 + 4**2 != 5**2

bool_five = not not False
```

9. This and That (or This, But Not That!)
```python
bool_one = False or not True and True

bool_two = False and not True or True

bool_three = True and not (False or False)

bool_four = not not True or False and not True

bool_five = False or not (True and True)
```

10 Mix 'n' Match
```python
# Use boolean expressions as appropriate on the lines below!

# Make me false!
bool_one = (2 <= 2) and "Alpha" == "Bravo"  # We did this one for you!

# Make me true!
bool_two = True and True

# Make me false!
bool_three = False and True

# Make me true!
bool_four = not False

# Make me true!
bool_five = True or True
```

11. Conditional Statement Syntax
```python
response = "Y"

answer = "Left"
if answer == "Left":
    print "This is the Verbal Abuse Room, you heap of parrot droppings!"
    
# Will the above print statement print to the console?
# Set response to 'Y' if you think so, and 'N' if you think not.
```

12. If You're Having...
```python
def using_control_once():
    if 2 > 1:
        return "Success #1"

def using_control_again():
    if 2 > 1:
        return "Success #2"

print using_control_once()
print using_control_again()
```

13. Else Problems, I Feel Bad for You, Son...
```python
answer = "'Tis but a scratch!"

def black_knight():
    if answer == "'Tis but a scratch!":
        return True
    else:             
        return False     # Make sure this returns False

def french_soldier():
    if answer == "Go away, or I shall taunt you a second time!":
        return True
    else:             
        return False     # Make sure this returns False
```

14. I Got 99 Problems, But a Switch Ain't One
```python
def greater_less_equal_5(answer):
    if answer > 5:
        return 1
    elif answer < 5:          
        return -1
    else:
        return 0
        
print greater_less_equal_5(4)
print greater_less_equal_5(5)
print greater_less_equal_5(6)
```

15. The Big If
```python
# Make sure that the_flying_circus() returns True
def the_flying_circus():
    if 5>4 and 4 > 3:    # Start coding here!
        # Don't forget to indent
        # the code inside this block!
        return True
    elif 3==3:
        # Keep going here.
        return False
        # You'll want to add the else statement, too
        
    else:
      return False
```

# PygLatin

1. Break It Down

2. Ahoy! (or Should I Say Ahoyay!)
```python
print 'Pig Latin'
```

3. Input!
```python
print 'Welcome to the Pig Latin Translator!'

# Start coding here!
original = raw_input("Enter a word: ")
```

4. Check Yourself!
```python
print 'Welcome to the Pig Latin Translator!'

# Start coding here!
original = raw_input("Enter a word: ")

if len(original) > 0:
  print original
else:
  print "empty"
```

5. Check Yourself... Some More
```python
print 'Welcome to the Pig Latin Translator!'

# Start coding here!
original = raw_input("Enter a word: ")

if len(original) > 0 and original.isalpha():
  print original
else:
  print "empty"
```

6. Pop Quiz!

7. Ay B C
```python
pyg = 'ay'
```

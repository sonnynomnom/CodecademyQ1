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

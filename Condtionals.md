# Codecademy Python

##### Python

1. Strings

```python
# Set the variable brian on line 3!

brian = "Hello life!"
```


2. Practice
```python
# Assign your variables below, each on its own line!

caesar = "Graham"
praline = "John"
viking = "Teresa"

# Put your variables above this line

print caesar
print praline
print viking
```

3. Escaping characters
```python
# The string below is broken. Fix it using the escape backslash!

'This isn\'t flying, this is falling with style!'
```

4. Access by Index
```python
"""
The string "PYTHON" has six characters,
numbered 0 to 5, as shown below:

+---+---+---+---+---+---+
| P | Y | T | H | O | N |
+---+---+---+---+---+---+
  0   1   2   3   4   5

So if you wanted "Y", you could just type
"PYTHON"[1] (always start counting from 0!)
"""
fifth_letter = "MONTY"[4]

print fifth_letter
```

5. String methods
```python
parrot = "Norwegian Blue"
print len(parrot)
```

6. lower()
```python
parrot = "Norwegian Blue"

print parrot.lower()
```

7. upper()
```python
parrot = "norwegian blue"

print parrot.upper()
```

8. str()
```python
"""Declare and assign your variable on line 4,
then call your method on line 5!"""

pi = 3.14
print str(pi)
```

9. Dot Notation
```python
ministry = "The Ministry of Silly Walks"

print len(ministry)
print ministry.upper()
```

10. Printing Strings
```python
"""Tell Python to print "Monty Python"
to the console on line 4!"""

print "Monty Python"
```

11. Printing Variables
```python
"""Assign the string "Ping!" to
the variable the_machine_goes on
line 5, then print it out on line 6!"""

the_machine_goes = "Ping!"
print the_machine_goes
```

12. String Concatenation
```python
# Print the concatenation of "Spam and eggs" on line 3!

print "Spam " + "and " + "eggs"
```

13. Explicit String Conversion
```python
# Turn 3.14 into a string on line 3!

print "The value of pi is around " + str(3.14)
```

14. String Formatting with %, Part 1
```python
string_1 = "Camelot"
string_2 = "place"

print "Let's not go to %s. 'Tis a silly %s." % (string_1, string_2)
```

15. String Formatting with %, Part 2
```python
name = raw_input("What is your name? ")
quest = raw_input("What is your quest? ")
color = raw_input("What is your favorite color? ")

print "Ah, so your name is %s, your quest is %s, " \
"and your favorite color is %s." % (name, quest, color)
```

16. And Now, For Something Completely Familiar
```python
# Write your code below, starting on line 3!

my_string = "blah"
print len(my_string)
print my_string.upper()
```

# Date and Time

1. The datetime Library
```python
from datetime import datetime
```

2. Getting the Current Date and Time
```python
from datetime import datetime

now = datetime.now()
print now
```

3. Extracting Information
```python
from datetime import datetime

now = datetime.now()
print now

print now.year
print now.month
print now.day
```

4. Hot Date
```python
from datetime import datetime
now = datetime.now()

print '%s/%s/%s' % (now.month, now.day, now.year)
```

5. Pretty Time
```python
from datetime import datetime
now = datetime.now()

print '%s:%s:%s' % (now.hour, now.minute, now.second)
```

6. Grand Finale
```python
from datetime import datetime
now = datetime.now()

print '%s/%s/%s %s:%s:%s' % (now.month, now.day, now.year, now.hour, now.minute, now.second)
```

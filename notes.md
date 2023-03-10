# Notes_Python
Notes regarding important information about Python


## -----------------> Interacting with OS

### -----------------> Basic commands in the terminal

==type== => to see the content of a file. Is the windows version of "cat" command with Linux
```
C:\Users\acer\Documents> type hello_world.py

```py

__python__ => to enter to the python interpreter and to execute a python file
__exit()__ => to exit to the python interpreter
__Import a file a use its function__ => pretty simple example of how to import and use functions:

```
C:\Users\acer\Documents> type areas.py
import math

def triangle(base, height):
    return base*height/2

def rectangle(base, height):
    return base*height

def circle(radius):
    return math.pi*(radius**2)
C:\Users\acer\Documents> python
Python 3.11.2 (tags/v3.11.2:878ead1, Feb  7 2023, 16:38:35) [MSC v.1934 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> import areas
>>> areas.triangle(3,5)
7.5
>>> areas.circle(8.9)
248.84555409084754
>>> round(areas.circle(8.9), 2)
248.85
```py

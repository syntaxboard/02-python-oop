---
YamlDesc: CONTENT-ARTICLE
Title: python class
MetaDescription: python class object oriented programming example code, tutorials
MetaKeywords: python, class, objects, object oriented programming, example code, tutorials
Author: Venkata Bhattaram / tinitiate.com
ContentName: print-class
---

# Object Oriented Programming Vs Functional Programming
* Here we demonstrate why Object Oriented Programming is more efficient than 
  Functional Programming for a same problem-solution

## Create a Class
* Here we create a Class to Add and Multiply TWO Numbers

'''
class Test:

    def add1(self, num1, num2):
        return num1 + num2

    def mul1(self, num1, num2):
        return num1 * num2

```


## Create the Class Object
* Here we create the class object and display the size of the object
```
from class_test import Test as t

Obj1 = t(100,200)

print(Obj1.__sizeof__())
```


## Create a functional code the same as Class
* Here we create a file with functional code, same as the Test Class to Add 
  and Multiply TWO Numbers.
  
```
num1 = None
num2 = None
        
def add1(self, num1, num2):
    return num1 + num2

def mul1(self, num1, num2):
    return num1 * num2
```


## Import Functionl Code File
* Here we import the Functionl Code File and assign the same values as in 
  the Object Oriented Programming.
* After assigning the values to the functional code caller, it proves that 
  the functionl code occupies more space, and proves that Object Oriented is 
  space efficient in similar business contexts.

```
import func_test as f

f.num1 = 100
f.num2 = 200

print(f.__sizeof__())
```

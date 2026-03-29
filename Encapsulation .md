# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program:
```
# Encapsulation example with private members

class Rectangle:
    
    def __init__(self, length, breadth):
        self.__length = length
        self.__breadth = breadth

    def display(self):
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)

# Create object
obj = Rectangle(10, 5)

# Access through method
obj.display()
```

## Output:

<img width="397" height="215" alt="image" src="https://github.com/user-attachments/assets/145c399a-2a63-40d0-b292-748bb28ed672" />

## Result:

Thus, the Python program demonstrating encapsulation using private member variables was successfully executed and verified.

## 💻 Program

## Output

## Result

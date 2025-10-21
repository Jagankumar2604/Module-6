# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** class has a concrete method sleep() that will be the same for all the child classes. For that purpose, define the sound() method as an abstract method. then implement it in all child classes.
---

## 🧠 ALGORITHM
Start

Import Abstract Class Module
Import ABC and abstractmethod from the abc module to define abstract base classes.

Define Abstract Class Animal

Create a class named Animal that inherits from ABC.

Inside it, define an abstract method sound() using the @abstractmethod decorator.

Leave the sound() method unimplemented (use pass).

Define Concrete Subclasses

Create subclasses Snake, Dog, Lion, and Cat, each inheriting from Animal.

In each subclass, implement the sound() method:

Snake: Print "I can hiss".

Dog: Print "I can bark".

Lion: Print "I can roar".

Cat: Print "I can meow".

Add Extra Behavior (Optional)

In the Cat class, define an additional method sleep() that prints "I am going to sleep in a while".

Create and Use Objects

Create an object of class Cat.

Call sleep() method — prints "I am going to sleep in a while".

Call sound() method — prints "I can meow".
Create an object of class Snake.
Call sound() method — prints "I can hiss".

End





---

## 💻 Program
```
from abc import ABC,abstractmethod
 
class Animal(ABC):
    
    @abstractmethod
    def sound(self):
        pass
class Snake(Animal):
    def sound(self):
        print("I can hiss")
 
class Dog(Animal):
    def sound(self):
        print("I can bark")
 
class Lion(Animal):
    def sound(self):
        print("I can roar")
       
class Cat(Animal):
    def sound(self):
        print("I can meow")
    def sleep(self):
        print("I am going to sleep in a while")
        
c=Cat()
c.sleep()
c.sound()
c=Snake()
c.sound()
```

## Output
<img width="775" height="237" alt="image" src="https://github.com/user-attachments/assets/830d6530-47a2-437d-9adc-1f3450f5c6f6" />


## Result
To create an **abstract class** class has a concrete method sleep() that will be the same for all the child classes. For that purpose, define the sound() method as an abstract method. then implement it in all child classes is Executed successfully.


# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by with the version as private member initialized with the value as 22 change the value of the private member using getter and setter methods and also display the value of the version variable.

---

## 🧠 ALGORITHM
1.Define a class Robot.

2.The constructor (init) initializes a private attribute __version with the value given as a parameter.

3.Define a method getVersion() to print the value of the private attribute __version.

4.Define a method setVersion(a) to update the value of the private attribute __version.

5.Create an instance obj of the Robot class with initial version 22.

6.Call obj.getVersion() to print the initial version (22).

7.Call obj.setVersion(23) to update the version to 23.

8.Call obj.getVersion() again to print the updated version (23).



---

## 💻 Program
```
class Robot:
   def __init__(self,a):
      self.__version = a

   def getVersion(self):
      print(self.__version)

   def setVersion(self,a):
      self.__version = a

obj = Robot(22)
obj.getVersion()
obj.setVersion(23)
obj.getVersion()

```

## Output
<img width="342" height="143" alt="image" src="https://github.com/user-attachments/assets/c01259ec-86bb-452e-a986-37640e010ffa" />



## Result
To implement **Encapsulation** in Python by with the version as private member initialized with the value as 22 change the value of the private member using getter and setter methods and also display the value of the version variable is executed successfully.

# start1
from abc import ABC, abstractmethod
class Animal(ABC):
    @abstractmethod
    def speak(self):
      pass
class Cat(Animal):
    def speak(self):
        return "Meow"


cat = Cat()
cat = cat.speak()
print(cat)

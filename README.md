<h1 align="center">Hi there 👋</h1>


```python
class MySelf:
    name = 'Ivan'
    surname = 'Zhilnikov'
    gender = 'male'
    age = 33
    studying = ['Python', 'Django', 'Flask', 'SQL', 'HTML', 'CSS', 'Rest API', 'Git', 'Linux']
    books = ['Grokking Algorithms', 'Code Complete']
    course = 'hexlet.io'
    tools = ['PyCharm', 'Obsidian', 'Ubuntu', 'Postman']

    def say_hello(self):
        print("Hi, my name is", self.name, self.surname)
        print("Gender:", self.gender)
        print("Age:", self.age)
        print("Studying now:", self.studying)
        print("Reading now:", self.books)
        print("I'm taking courses from:", self.course)
        print("Using tools:", self.tools)


# Creating an instance of the class
obj = MySelf()
obj.say_hello()

```

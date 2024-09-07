# 04
#1) CREATE A DICTIONARY
 student = {
   'name' : 'musharraf',
   'age' : 22,
   'major': 'computer science'
 }
 
 print(student)
 print(student['name'])
 print(student['age'])
 print(student['major'])
 student['major'] = 'mathematics'
 print(student['major'])

#2) 
 info = {
   'name' : 'musharraf',
   'age' : 22,
   'standard': 'first year',
   'subject' : 'computer',
   'roll_no' : 21
   }
 
 print(info['name'])
 print(info['age'])
 print(info['roll_no'])
 info['roll_no'] = 23
 print(info['roll_no'])
 info['D_O_B'] = 19_08_2002
 print(info['D_O_B'])

 #3)
 product = {
  'name' : 'biscuit',
  'price': 25,
  'made_in' : 'india',
  'ingredient' : 'vitamis'
  }
 
 print(product)
 print(product['name'])
 print(product['made_in'])
 print(product['ingredient'])
 product['price'] = 30
 print(product['price'])

 #1)
 class Student:
  name = 'musharraf'
  
s1 = Student()
print(s1.name)

#2)
class Student:
  name = 'musharraf'

s1 = Student()
print(s1.name)

s2 = Student()
print(s2.name)

#3)
class Car:
  color = 'blue'
  brand = 'mercedes'

car1 = Car()
print(car1.color)
print(car1.brand)

#4)
class Student:
    def __init__(self,fullname):
      self.name = fullname
      print("adding new student in database")


s1 = Student("musharraf")
print(s1.name)

#5)
class Student:
  def __init__(self,fullname):
    self.name = fullname
    print("adding new student in database.")


s1 = Student("khan")
print(s1.name)

s2 = Student("shaikh")
print(s2.name)

#6)
class Student:

   def __init__(self, name, marks):
       self.name = name
       self.marks = marks
       print("adding new student in database")


s1 = Student("shoeb",90)
print(s1.name,s1.marks)

s2 = Student("shaid",95)
print(s2.name,s2.marks)

#7)
class Student:

  def __init__(self):
    pass


  def __init__(self, name, marks):
    self.name = name
    self.marks = marks
    print("adding new student in database")


s1 = Student(marks = 78, name = "khan")
print(s1.name,s1.marks)

s2 = Student(marks = 65, name = "shaikh")
print(s2.name,s2.marks)

#8)


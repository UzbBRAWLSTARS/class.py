class Student:


    def __init__(self,name,surname,age,level):
        self.name = name
        self.surname = surname
        self.age = age
        self.level = level

student = Student("Zarina","Axmedova",18,2)
student2 = Student("Zafar","Axmedov",20,4)
print(student.name)
print(student2.name)

class Car:

    def __init__(self,name,brand,year,color,speed):
        self.name = name
        self.brand = brand
        self.year = year
        self.color = color
        self.speed = speed
    
    #method
    def get_info(self):
        return f"Ajoyib tanlov!!! Moshinaning nomi {self.name} brandi {self.brand} chiqarilgan yili {self.year} rangi esa {self.color} tezligi {self.speed}"

    def __str__(self):
        return f"{self.name}"


car1 = Car(">>>Malibu<<<","Chevrolet",2020,"qora","250 km/h")
car2 = Car(">>>Nexia<<<","Chevrolet",2005,"oq","180 km/h")
car3 = Car(">>>Malibu 2<<<","Chevrolet",2021,"qora","260 km/h")
car4 = Car(">>>Nexia 3<<<","Chevrolet",2018,"qaymoqrang","210 km/h")
car5 = Car(">>>Lada<<<","Chevrolet",2022,"sariq","300 km/h")

print(car1.get_info())
print(car2.get_info())
print(car3.get_info())
print(car4.get_info())
print(car5.get_info())
print("Byaqqa  kelllll")

print(car1.name)
print(car1.brand)
print(car1.year)
print(car1.color)
print(car1.speed)
print(car2.name)
print(car2.brand)
print(car2.year)
print(car2.color)
print(car2.speed)
print(car3.name)
print(car3.brand)
print(car3.year)
print(car3.color)
print(car3.speed)
print(car4.name)
print(car4.brand)
print(car4.year)
print(car4.color)
print(car4.speed)
print(car5.name)
print(car5.brand)
print(car5.year)
print(car5.color)
print(car5.speed)


class User:
    def __init__(self,nick,name,email,birthday):
        self.nick = nick
        self.name = name
        self.email = email
        self.birthday = birthday

    def get_info(self):
        return f"Foydalanuvchi: {self.nick}, ismi: {self.name},tug'ilgan yili: {self.birthday}, email: {self.email}."   

user1 = User("Alij@n007","Ali","alijon2007@gmail.com","2007-yil")
user2 = User("Gulya","Gulchapchak","gulya1997@gmail.com","2001-yil")

print(user1.get_info())
print(user2.get_info())

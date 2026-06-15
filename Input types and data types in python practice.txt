
#greeting program

name= input("What is your name? ")

print ("Hello",name )

#Adding numbers

'''

num1= input("Enter first number:") #change to integer as pyt connects string

num2= input("Enter second number")

'''

num1= int(input("Enter first number:"))

num2 =int(input("Enter second number:"))

total=num1 + num2

print ("Answer =", total)

#Age in five years

age= int(input("Enter your current age:"))

Future_age= age+5

print ("In five years you will be",Future_age)

#Favourite fruits

fruit1 = input("Fruit 1: ")
fruit2 = input("Fruit 2: ")
fruit3 = input("Fruit 3: ")

fruits = [fruit1, fruit2, fruit3]

print(fruits)
print("First fruit:", fruits[0])
 
'''
Index 0 :First item
Index 1 : Second item
Index 2 : Third item

'''
#Student dictionary

name = input("Enter name: ")
age = int(input("Enter age: "))

student = {
    "name": name,
    "age": age
              } 

print(student)
print("Student name:", student["name"])

#Profile program

name = input("Name: ")
age = int(input("Age: "))
city = input("City: ")

profile = {
    "name": name,
    "age": age,
    "city": city
}

print()
print("PROFILE")
print("-------")
print("Name:", profile["name"])
print("Age:", profile["age"])
print("City:", profile["city"])
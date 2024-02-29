name= input("Enter your name: ")
age = int(input("Enter your age: "))
location = input("Enter your location: ")

#first approach
print("Hello ", name, " you are ", age, "year old and live in ", location)

#second approach %
print("second aproach")
print(" Hello %s your %d years old and you live %s"%(name, age, location))

#third approach format 
print("third approach")
print("Hello {} your {} years old and you live in {}".format(name, age, location))
 

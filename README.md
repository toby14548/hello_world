#this is my first complete code

print("calculator")

def calculator1(name1):
    First = input("input first number:" )
    Second = input("input second number:" )
    answer = int(First) + int(Second)
    print(answer)

def calculator2(name2):
    First = input("input first number:" )
    Second = input("input second number:" )
    answer = int(First) * int(Second)
    print(answer)

def calculator3(name3):
    First = input("input first number:" )
    Second = input("input second number:" )
    answer = int(First) / int(Second)
    print(answer)

def calculator4(name4):
    First = input("input first number:" )
    Second = input("input second number:" )
    answer = int(First) - int(Second)
    print(answer)

addition = True
subtraction = True
multiplication = True
division = True

if addition :
    calculator1("print")
    
if subtraction :
    calculator4("print")

if multiplication :
    calculator2("print")

if subtraction :
    calculator3("print")

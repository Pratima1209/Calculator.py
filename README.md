# Calculator.py

# Calculator Program

def add(x,y):
    return x+y

def sub(x,y):
    return x-y

def multy(x,y):
    return x*y

def div(x,y):
    return x/y

def mod(x,y):
    return x//y

print ("Select the operation 1,2,3,4,5 :")
print ("1.Addition")
print ("2.Substract")
print ("3.Multipy")
print ("4.Divide")
print ("5.Mod")

select =input("Please Enter the number for operation :")
num1=input("Enter the number1 :")
num2=input("Enter the number2 :")

if select == 1:
    print("Answer =",add(num1,num2))

elif select == 2:
    print("Answer =",sub(num1,num2))

elif select == 3:
    print("Answer =",multy(num1,num2))

elif select == 4:
    print("Answer =",div(num1,num2))

elif select == 5:
    print("Answer =",mod(num1,num2))

else:
    print("Invalid Number")




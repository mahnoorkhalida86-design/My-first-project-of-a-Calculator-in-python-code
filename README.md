# My-first-project-of-a-Calculator-in-python-code
print("Welcome to this program")
while True:
 def add(a,b):
     return a+b
 def sub(a,b):
    return a-b
 def mul(a,b):
    return a*b
 def div(a,b):
    return a/b
 def pow(a,b):
    return a**b
 def mod(a,b):
    return a%b
 a=int(input("Enter the first number"))
 b=int(input("Enter the second number"))
 choice=int(input("Enter your choice such as 1.addition 2.subtraction 3.multiplication 4.division 5.power 6.modulus"))
 if choice==1:
  print("SUM of Given Numbers is",add(a,b))
 elif choice==2:
  print("SUBTRACTION of Given Numbers is",sub(a,b))
 elif choice==3:
  print("MULTIPLICATION of Given Numbers is",mul(a,b))
 elif choice==5:
  print("POWER of Given Numbers is",pow(a,b))
 elif b==0 and choice==4:
    print("b is zero")
 elif b!=0 and choice==4:
    print("DIVISION of Given Numbers is",div(a,b))
 elif choice==6 and b==0:
     print("b is zero")
 elif choice==6 and b!=0:
     print("Modulus of Given Numbers is", mod(a, b))
 else:
    print("Your choice is invalid")

 check=input("Enter y if you want to continue and n for exit").lower()
 if check!='y':
     break
print("Thank you for using this program")

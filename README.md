# Simple-calculator
a=int(input("Enter a number: "))
b=int(input("Enter a number: "))
print('+,''-,''*,''/,''**,''%,''//')
c=str(input("Enter your choice: "))
if (c=="+"):
    print("Answer is",a+b)
elif (c=="-"):
    print("Answer is",a-b)
elif (c=="*"):
    print("Answer is",a*b)
elif (c=="/"):
    print("Answer is",a/b)
elif (c=="**"):
    print("Answer is",a**b)
elif (c=="%"):
    print("Answer is",a%b)
elif(c=="//"):
    print("Answer is",a//b)
else:
    print("SELECT CORRECT OPTION")

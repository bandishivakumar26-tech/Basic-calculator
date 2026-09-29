# Basic-calculator
Easy by python
a=int(input("Enter a: "))
b=int(input("Enter b:"))
cal=input("enter any operation (+,-,/,*):")
if cal=='-':
    print(a-b)
elif cal=='+':
    print(a+b)
elif cal=='/':
    print(a/b)
elif cal=='*':
    print(a*b)
else:
    print("invalid operation")


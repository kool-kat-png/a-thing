import sys
from math import sqrt,factorial,log
sys.set_int_max_str_digits(999999999)
on=True
ans=1
errors=[]
while on:
    try:
        op=float(input("pick one:1.add 2.subtract 3.multiply 4.divide 5.exponent 6.square root 7.factorial 8.logarithm"))
        if op==1:
            num1=input("number 1:")
            if num1=="ans":
                num1=ans
            else:
                num1=float(num1)
            num2=input("number 2:")
            if num2=="ans":
                num2=ans
            else:
                num2=float(num2)
            if len(str(num1+num2))>999999999:
                print("number is too big to show")
            else:
                print(f"{num1}+{num2}=",num1+num2)
                ans=num1+num2
        elif op==2:
            num1=input("number 1:")
            if num1=="ans":
                num1=ans
            else:
                num1=float(num1)
            num2=input("number 2:")
            if num2=="ans":
                num2=ans
            else:
                num2=float(num2)
            if len(str(num1-num2))>999999999:
                print("number is too big to show")
            else:
                print(f"{num1}-{num2}=",num1-num2)
                ans=num1-num2
        elif op==3:
            num1=input("number 1:")
            if num1=="ans":
                num1=ans
            else:
                num1=float(num1)
            num2=input("number 2:")
            if num2=="ans":
                num2=ans
            else:
                num2=float(num2)
            if len(str(num1*num2))>999999999:
                print("number is too big to show")
            else:
                print(f"{num1}*{num2}=",num1*num2)
                ans=num1*num2
        elif op==4:
            num1=input("number 1:")
            if num1=="ans":
                num1=ans
            else:
                num1=float(num1)
            num2=input("number 2:")
            if num2=="ans":
                num2=ans
            else:
                num2=float(num2)
            if len(str(num1/num2))>999999999:
                print("number is too big to show")
            else:
                print(f"{num1}/{num2}=",num1/num2)
                ans=num1/num2
        elif op==5:
            num1=input("number 1:")
            if num1=="ans":
                num1=ans
            else:
                num1=float(num1)
            num2=input("number 2:")
            if num2=="ans":
                num2=ans
            else:
                num2=float(num2)
            if len(str(num1**num2))>999999999:
                print("number is too big to show")
            else:
                print(f"{num1}^{num2}=",num1**num2)
                ans=num1**num2
        elif op==6:
            num1=input("number 1:")
            if num1=="ans":
                num1=ans
            else:
                num1=float(num1)
            num2=input("number 2:")
            if num2=="ans":
                num2=ans
            else:
                num2=float(num2)
            if len(str(num1 ** (1. / num2)))>999999999:
                print("number is too big to show")
            else:
                print(f"the {num2} root of {num1}=",num1 ** (1. / num2))
                ans=sqrt(num1)
        elif op==7:
            num1=input("integer:")
            if num1=="ans":
                num1=ans
            else:
                round(float(num1))
                num1=int(num1)
            if len(str(factorial(num1)))>999999999:
                print("number is too big to show")
            else:
                print(f"the factorial of {num1}=",factorial(num1))
                ans=factorial(num1)
        elif op==8:
            num1=input("number:")
            if num1=="ans":
                num1=ans
            else:
                num1=float(num1)
            num2=input("base:")
            if num2=="ans":
                num2=ans
            else:
                num2=float(num2)
                
            if len(str(log(num1,num2)))>999999999:
                print("number is too big to show")
            else:
                print(f"{num1} log {num2}=",log(num1,num2))
                ans=log(num1,num2)
        if input("continue? (yes/no)")=="no":
            on=False
    except Exception as e:
        if input("error")=="dev":
            print(e)
        errors.append("--spacing--")
        errors.append(e)
if input("bye now!")=="dev":
    print(errors)

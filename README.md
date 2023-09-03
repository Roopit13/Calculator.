# Calculator.
#A python program to apply BODMAS on two numbers
c=input("Enter the operator: ")
num1=input("Enter Number 1: ")
num2=input("Enter Number 2: ")
match c:
    case '+':
        res=float(num1)+float(num2)
    case '-':
        res=float(num1)-float(num2)    
    case '*':
        res=float(num1)*float(num2)
    case '/':
        res=float(num1)/float(num2)
print(num1,c,num2,"=",res)                

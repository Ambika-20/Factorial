# Factorial
def fact(n):
    if n==0:
        return 1
    else:
        return(n*fact(n-1))
n= int(input("Enter a num:"))
result=fact(n)
print("Factorial of",n,"is",fact(n))

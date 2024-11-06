# Program to print pyramid 
n=int(input("enter no. of rows")
for i in range(1, n + 1):
      for j in range(n - i):
          print(" ", end="")
      for k in range(1, 2*i):
          print"*", end="")
      print()


# Program to Print inverted pyramid
n=int(input("rows"))
for i in range(n, 0, -1):
      for j in range(n - i):
            print(" ", end="")
      for k in range(2*i - 1):
            print("*", end="")
      print("")

# Program to find roots of quadratic equation
a,b,c=eval(input("enter value of a,b,c")
d=b**2-4a*c
if d>=0:
    x=d**0.5
    r1=(-b+x)/2*a
    r2=(-b-x)/2*a
    print("real roots exist=",r1,r2)
elif d<0:
    print("real roots do not exist")

# Program to check if given no. is prime 
n=int(input("enter a no."))
for i in range(2,n):
        if (n % i) == 0:
            print(n, "is not a prime number")
            break
        else:
            print(n, "is a prime number")
else:
    print(n, "is not a prime number

# Program to generate all prime nos till asked
n=int(input("enter a no."))
for i in (1,n+1):
    if 



    

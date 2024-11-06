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

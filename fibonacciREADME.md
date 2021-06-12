# fibonacci-series
num = int(input("How many terms of fibonacci numbers do you need?"))
n1, n2 = 0, 1
count = 0
if num <= 0:
   print("Please enter a positive number:")
elif num == 1:
   print("Fibonacci sequence upto", num, ":")
   print(n1)
else:
   print("Fibonacci sequence:")
   while count < num:
        print(n1)
        nth = n1 + n2
        n1 = n2
        n2 = nth
        count = count + 1

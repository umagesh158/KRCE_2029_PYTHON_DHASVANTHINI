#Q1
n = int(input())
if 1000 <= n <= 9999 and n // 1000 > n % 10 and (n % 3 == 0 or n % 7 == 0) and (n // 10) % 10 != (n // 100) % 10:
    print("Valid")
else:
    print("Invalid")

#Q2

n=int(input())
if n <= 100:
    bill = n * 2
elif n <= 200:
    bill = 200 + (n - 100) * 3
elif n <= 500:
    bill = 500 + (n - 200) * 5
else:
    bill = 2000 + (n - 500) * 7
if bill > 2000:
    bill = bill + bill * 5 // 100
if n % 50 == 0:
    bill = bill - 100
print(bill)

#Q3

a=int(input())
b=int(input())
c=int(input())
if (a > b and a < c) or (a < b and a > c):
    print(a)
elif (b > a and b < c) or (b < a and b > c):
    print(b)
else:
    print(c)
    

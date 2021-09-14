# BinaryDigitsTable
Compute the binary digits of an integer to print a table,  followed by a statement of the binary representation of the integer.

n = int(input())
b = ""
print("x x//2 x%2")
"89 44 1"
"44 22 0"
"22 11 0"
"11 5 1"
"5 2 1"
"1 0 1"
w = n
while n!=0:
    b = str(n%2) + b
    print (n, n//2, n%2)
    n = n//2
print("Therefore,", str(w), "=", "0b" + b)

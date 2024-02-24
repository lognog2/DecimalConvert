# Decimal to Binary converter by Logan Nyquist
# 1.0: Program can convert any positive decimal number to its binary equivalent (2/2024)
import cmath

# ask user for positive int
num = 0
while (num <= 0):
    num = input("enter a positive integer: ")
    # error checking
    if (num.isdigit()): num = int(num)
    else: num = 0

# find length in binary
length = 0
found = False
while (found == False):
    if (pow(2, length) > num):
        found = True
    else: length += 1

# build binary number as array of ints
binary = []
for i in range(0,length):
    if (num >= pow(2,(length-1-i))):
        binary.append(1)
        num -= pow(2,(length-1-i))
    else:
        binary.append(0)

# print result
for i in binary:
    print(i, end="")
        

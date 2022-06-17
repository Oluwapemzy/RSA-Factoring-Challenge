#!/usr/bin/python3
import sys
my_arg = sys.argv
foo = open(file=my_arg[1], mode="r")
for num in foo:
    num = int(num)
    for val in range(2, int(num ** 0.5) + 1):
        if num % val == 0:
            print(f"{int(num)} = {int(num) // val}*{val}")
            break

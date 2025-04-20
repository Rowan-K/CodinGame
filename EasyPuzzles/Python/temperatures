import sys
import math
# https://www.codingame.com/ide/puzzle/temperatures
# Auto-generated code below aims at helping you parse
# the standard input according to the problem statement.


n = int(input())  # the number of temperatures to analyse


if n == 0:
    print(0)
else:
    min_t = 5527
    for i in input().split():
        # t: a temperature expressed as an integer ranging from -273 to 5526
        t = int(i)
        if abs(t) < abs(min_t) or (abs(t) == abs(min_t) and t > min_t):
            min_t = t
    print(min_t)

# Basic-Age-Calculator
This is my basic age calculator :)
x1 = input("Type your birth's year (0000): ")
x1t = int(x1)

x2 = input("Type your birth's month (00): ")
x2t = int(x2)
x3 = input("Type your birth's day (00): ")
x3t = int(x3)
y1 = input("\nAnd now type today's year (0000): ")
y1t = int(y1)
y2 = input("Type today's month (00): ")
y2t = int(y2)
y3 = input("Type today's day (00): ")
y3t = int(y3)

ty = y1t - x1t
tm = y2t - x2t
td = y3t - x3t

t = ty, tm, td
tt = str(t)

print('Your age is', tt)
input("Press 'ENTER' to exit: ")

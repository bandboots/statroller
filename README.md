import random
a = []
b = []
i = 0
j = 0

while i < 6:
    while j < 4:
        n = random.randint ( 1 , 6 )
        b.append ( n )
        j += 1
    b.sort()
    del b[0]
    a.append ( sum ( b ) )
    b = []
    j = 0
    i += 1
print a

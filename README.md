printed = 0
for i in range(100, 201):
    if i % 4 == 0 and i % 5 == 0:
        continue
    if i % 4 != 0 and i % 5 != 0:
        continue
    print(i, end=" ")
    if (printed := printed+1) == 10:
        printed = 0
        print()

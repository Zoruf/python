a = int(input())

b = int(input())

h = int(input())

if a <= b:

    if h < a:
        print("Недосып")

    elif h > b:
        print("Пересып")

    else:
        print("Это номально")

else:
    print("Fuck you")

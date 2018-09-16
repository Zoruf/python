n = int(input())

if n % 10 == 0 or (n % 10 >= 5 and n % 10 <= 9):
    end = "ов"

elif n % 10 ==1:
    end = ""

elif n % 10 > 1 and n % 10 < 5:
    end = "а"

elif n > 21 and n < 10:
    end = "ов"

prog = " программист" + end

result = str(n) + prog

print(result)

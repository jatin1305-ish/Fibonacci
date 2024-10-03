# Fibonacci
Fibonacci heap performing with reccrusion
def Fibonacci(n):

    # Check if input is 0 then it will
    # print correct input
    if n < 0:
        print("correct input")

    # Check if n is 0
    # then it will return 0
    elif n == 0:
        return 0

    # Check if n is 1,2
    # it will return 1
    elif n == 1 or n == 2:
        return 1

    else:
        return Fibonacci(n-1) + Fibonacci(n-2)


# Driver Program
print(Fibonacci(9))

output:- 34

def add(num1, num2):
    return num1 + num2

def sub(num1, num2):
    return num1 - num2

def mul(num1, num2):
    return num1 * num2

def div(num1, num2):
    return num1 / num2

def main():
    num1 = float(input("What is the first number? "))
    num2 = float(input("What is the second number? "))
    operation = input("What do you want to do? (add, sub, mul, div): ").strip().lower()

    if operation == "add":
        print(add(num1, num2))
    elif operation == "sub":
        print(sub(num1, num2))
    elif operation == "mul":
        print(mul(num1, num2))
    elif operation == "div":
        print(div(num1, num2))
    else:
        print("Invalid input")

main()

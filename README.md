# calculator
creating a calculator

input_1 = int(input("Enter the first number:"))
input_2 = input("Enter an operation, such as +, -, / etc:")
input_3 = int(input("Enter the second number:"))
if input_2 == '+':
    print(f"{input_1} + {input_3} = ", input_1 + input_3)
elif input_2 == '-':
    print(f"{input_1} - {input_3} =", input_1 - input_3)
elif input_2 == '*':
    print(f"{input_1} * {input_3} =", input_1 * input_3)
elif input_2 == '/':
    if input_3 == 0:
        print("Error: Division by zero is not allowed.")
    print(f"{input_1} / {input_3}=", input_1 / input_3)
else:
    print("Invalid operation. Please enter +, -, *, or /.")


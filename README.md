# Python-Assgnment
 # Ask the user for input
    num1 = float(input("Enter the first number: "))
    num2 = float(input("Enter the second number: "))
    operation = input("Enter the operation (+, -, *, /): ")

    # Perform the calculation
    result = calculate(num1, num2, operation)

    # Display the result
    print(f"{num1} {operation} {num2} = {result}")

# Run the program
if __name__ == "__main__":
    main()

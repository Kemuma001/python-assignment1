Create a simple Python program that asks the user to input two numbers and a mathematical operation (addition, subtraction, multiplication, or division
    num1 = float(input("Enter the first number: "))
    num2 = float(input("Enter the second number: "))
    operation = input("Choose an operation (addition, subtraction, multiplication, division): ").strip().lower()

    # Perform the calculation based on the chosen operation
         if operation == "addition":
           result = num1 + num2
                print(f"The result of addition is: {result}")
        elif operation == "subtraction":
           result = num1 - num2
               print(f"The result of subtraction is: {result}")
        elif operation == "multiplication":
           result = num1 * num2
               print(f"The result of multiplication is: {result}")
        elif operation == "division":
            if num2 != 0:
             result = num1 / num2
               print(f"The result of division is: {result}")
       else:
              print("Error: Division by zero is not allowed.")
      else:
              print("Invalid operation. Please choose from addition, subtraction, multiplication, or division.")



2.Perform the operation based on the user's input and print the result.

      # Define the numbers
        num1 = 7
        num2 = 9

    # Calculate the sum
        result = num1 + num2

    # Display the result
        print(f"The sum of {num1} and {num2} is {result}.")
        The sum of 7 and 9 is 16.




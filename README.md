# Calculator

LANGUAGE-PYTHON

THIS FUNCTIONS ADD TWO NUMBERS

    def add(x, y):
    return x + y

THIS FUNCTIONS SUBTRACTS TWO NUMBERS

    def subtract(x, y):
    return x - y

THIS FUNCTIONS MULTIPLY TWO NUMBERS

    def multiply(x, y):
    return x * y

THIS FUNCTIONS DIVIDE TWO NUMBERS

     def divide(x, y):
     if y == 0:

CODE

      def add(x, y):
      return x + y

      def subtract(x, y):
      return x - y

      def multiply(x, y):
      return x * y

      def divide(x, y):
      if y == 0:
           return "Error! Division by zero is not allowed."
           else:
                 return x / y

       print("Select operation:")
       print("1. Addition")
       print("2. Subtraction")
       print("3. Multiplication")
       print("4. Division")

          while True:
          try:
       choice = int(input("Enter the number of the operation you'd like to perform: "))
       if choice in (1, 2, 3, 4):
           break
       else:
           print("Invalid input. Please enter a number between 1 and 4.")
    except ValueError:
       print("Invalid input. Please enter a number between 1 and 4.")

     num1 = float(input("Enter the first number: "))
     num2 = float(input("Enter the second number: "))

    if choice == 1:
       print(num1, "+", num2, "=", add(num1, num2))
    elif choice == 2:
       print(num1, "-", num2, "=", subtract(num1, num2))
    elif choice == 3:
       print(num1, "*", num2, "=", multiply(num1, num2))
    elif choice ==4:
      print(num1, "/", num2, "=", Divison(num1, num2))
    else:
       print("invalid Input")


   

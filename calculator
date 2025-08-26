def add(a, b):
    return a + b  #add the number

def subtract(a, b):
    return a - b  # subtract 

def multiply(a, b):
    return a * b

def divide(a, b):
    return a / b

def main():
    print("Simple Command-Line Calculator")
    print("Operations: add, sub, mul, div") # help to the use what he want to do 
    print("Enter 'exit' to quit") # to solve the issue and help to do work eassy 
    
    while True:
        operation = input("\nEnter operation (add, sub, mul, div) or 'exit' to quit: ").strip().lower()
        
        if operation == 'exit':
            print("Exiting calculator. Goodbye!")
            break
            
        if operation not in ['add', 'sub', 'mul', 'div']:
            print("Invalid operation. Please choose from add, sub, mul, div.")
            continue
            
        try:
            num1 = float(input("Enter first number: "))
            num2 = float(input("Enter second number: "))
        except ValueError:
            print("Invalid input. Please enter numeric values.")
            continue
            
        if operation == 'add':
            result = add(num1, num2)
        elif operation == 'sub':
            result = subtract(num1, num2)
        elif operation == 'mul':
            result = multiply(num1, num2)
        elif operation == 'div':
            if num2 == 0:
                print("Error: Division by zero is not allowed.")
                continue
            result = divide(num1, num2)
            
        print(f"Result: {result}")

if __name__ == "__main__":
    main()

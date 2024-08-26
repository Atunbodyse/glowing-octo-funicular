Question 1

def calculate_statistics(data):
    # Calculate sum
    total = sum(data)
    
    # Calculate average
    average = total / len(data)
    
    # Find minimum value
    minimum = min(data)
    
    # Find maximum value
    maximum = max(data)
    
    return total, average, minimum, maximum

# Example usage:
numbers = [12, 45, 7, 23, 56, 89, 34]
total, average, minimum, maximum = calculate_statistics(numbers)

print("Sum:", total)
print("Average:", average)
print("Minimum:", minimum)
print("Maximum:", maximum)

Question 2

def convert_to_float(n):
    return float(n)

# Example usage:
integer_number = 10
float_number = convert_to_float(integer_number)

print("Integer:", integer_number)
print("Float:", float_number)

# Alternatively, you can directly convert an integer to float without a function
integer_number = 20
float_number = float(integer_number)

print("Integer:", integer_number)
print("Float:", float_number)

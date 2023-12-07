# Walrus-Operator
The Walrus Operator (:=) is a feature in Python that allows the assignment of values to variables as part of a larger expression. 



Code Example:


print(a := False)  # Output: False
print(b := 8)      # Output: 8
print(aagya := "name")

# Walrus Operator in a while loop
numbers = [1, 2, 3, 4, 5]
while (n := len(numbers)) > 0:
    print(numbers.pop())

# Output of the while loop:
# 5
# 4
# 3
# 2
# 1

print(Happy := True)  # Output: True
Why the Name "Walrus"?
The syntax := resembles a walrus if you tilt your head to the right. This operator provides a convenient way to assign values within expressions, contributing to cleaner and more efficient code.



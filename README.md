# Assignment1

Here's one way using arithmetic operations:

Output
x: 10
y: 5

x = 5
y = 10

# Swap the values of x and y without using a temporary variable
x = x + y  # x becomes 15 (5 + 10)
y = x - y  # y becomes 5 (15 - 10)
x = x - y  # x becomes 10 (15 - 5)

print("x:", x)
print("y:", y)

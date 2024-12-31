#This is just a super simple project I did with Hyperskill

# Arbitrary numbers from project
# Used \n to make it more readable

print('''Prices:
Bubblegum: $2
Toffee: $0.2
Ice cream: $5
Milk chocolate: $4
Doughnut: $2.5
Pancake: $3.2\n''')

# Arbitrary numbers from project
# Used \n to make it more readable

print('''Earned amount:
Bubblegum: $202
Toffee: $118
Ice cream: $2250
Milk chocolate: $1680
Doughnut: $1075
Pancake: $80\n''')

# Simple math to find the 'income'

income = 202 + 118 + 2250 + 1680 + 1075 + 80 / 1

print(f"Income: ${income}")

# This takes the arbitrary input from the 'Accountant'
# Uses the \n to make format more readable

staff = int(input("Staff expenses:\n"))
other = int(input("Other expenses:\n"))

# Simple math problem for 'Accountant'

net = income - staff - other
print(f"Net Income: ${net}")

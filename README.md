# This code repeatedly prints all numbers less than or equal to 50. 
# If the number is greater than  50, it doesn't get printed out. Rather, it is displayed on the screen that the number is greater than 50.
for i in range(101):
  print(i) if i <= 50 else print(f'The number {i} is greater than 50')

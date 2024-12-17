# Code_Challenge8.py
print("Hey there! Let's play a game with numbers. I need you to give me 10 of them.")

numbers = []
even_numbers = []
odd_numbers = []
sum_of_numbers = []

for i in range(10):
    	number = int(input(f"Please enter number {i+1}: "))
if number % 2 == 0:
	even_numbers.append(number)
else:
    	odd_numbers.append(number)

sum_of_numbers = sum(numbers)
sum_of_even_numbers = sum(even_numbers)
sum_of_odd_numbers = sum(odd_numbers)

print(f"The sum of the numbers is: {sum_of_numbers}")
print(f"The sum of the even numbers is: {sum_of_even_numbers}")
print(f"The sum of the odd numbers is: {sum_of_odd_numbers}")

print("Thank you for using the program")

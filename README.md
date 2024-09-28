# Python-Basic-Project-1
By using python programming language .

# Find the Largest of Three Numbers .
# Write a program that finds the largest number between the three given numbers.

# Get a User Input from 3 users .

number_one = (int(input("Enter the 1st number : ")))
number_two = (int(input("Enter the 2nd number : ")))
number_three = (int(input("Enter the 3rd number : ")))

# Write the condition to checkout the largest number between the 3 numbers .

if number_one > number_two and number_one > number_three :
    print(f"The 1st number {(number_one)} is largest number compare to 2nd and 3rd number .")

elif number_two > number_one and number_two > number_three :
    print(f"The 2nd number {(number_two)} is largest number compare to 1st and 3rd number .")

elif number_three > number_one and number_three > number_two :
    print(f"The 3rd number {(number_three)} is largest number compare to 1st and 2nd number .")

elif number_one == number_two :
    print(f"The 1st number {number_one} and 2nd number {number_two} both are equal .")

elif number_one == number_three :
    print(f"The 1st number {number_one} and 3rd number {number_three} both are equal .")

elif number_two == number_three :
    print(f"The 2nd number {number_two} and 3rd number {number_three} both are equal .")

elif number_two == number_one :
    print(f"The 2nd number {number_two} and 1st number {number_one} both are equal .")

elif number_three == number_one :
    print(f"The 3rd number {number_three} and 1st number {number_one} both are equal .")

elif number_three == number_two :
    print(f"The 3rd number {number_three} and 2nd number {number_two} both are equal .")

else :
    print("Something Is Wrong !\nTry Again Later !")

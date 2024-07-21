# Question-To-be-asked

#QUESTION 1 
#Explaination of try
#After semi colon why are gaps mandatory

Doubt On These Concept yashu3047a

name = input("Enter your name: ")

while True:
    try:
        age = int(input("Enter your age: "))
        break  # Exit the loop if age is a valid integer
    except ValueError:
        print("Error: Please enter a valid number for age.")

age_after_10_years = age + 10  # Correcting the calculation to add 10 years

print(f"Hello {name}, after 10 years you will be {age_after_10_years} years old.")

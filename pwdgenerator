import random
import string

# Function to generate a list of secure passwords
def generate_passwords(amount):
    passwords = []
    special_characters = ['!', '#'] # Set of allowed special characters

    for _ in range(amount):
        
        # Ensure the password includes at least:
        # one uppercase letter, one digit, and one special character
        upper_case_letter = random.choice(string.ascii_uppercase)
        number = random.choice(string.digits)
        special_character = random.choice(special_characters)

        # Generate 14 additional random characters (letters + digits)
        other_characters = random.choices(string.ascii_letters + string.digits, k=14)

        # Combine all characters and shuffle to randomize order
        password_list = [upper_case_letter, number, special_character] + other_characters
        random.shuffle(password_list)

        # Join the list into a single string and add to the result list
        password = ''.join(password_list)
        passwords.append(password)

    return passwords

# Ask the user how many passwords to generate
try:
    count = int(input("How many passwords would you like to generate? "))
    if count < 1:
        print("Needs to be atleast one.")
    else:
        generated_passwords = generate_passwords(count)
        print("Generated passwords:")
        for password in generated_passwords:
            print(password)
except ValueError:
    print("Give an actual number.")

import re

# Function to validate password
def validate_password(password):
    # Check if the password length is at least 8 characters
    if len(password) < 8:
        return "Password must be at least 8 characters long."

    # Check if the password contains at least one letter
    if not re.search(r'[A-Za-z]', password):
        return "Password must contain at least one letter."

    # Check if the password contains at least one number
    if not re.search(r'[0-9]', password):
        return "Password must contain at least one number."

    # Check if the password contains at least one special character
    if not re.search(r'[@#$%^&+=!]', password):
        return "Password must contain at least one special character (@, #, $, etc.)."

    return "Your password is strong!"

# Take user input
password = input("Enter your password: ")

# Validate and print the result
result = validate_password(password)
print(result)

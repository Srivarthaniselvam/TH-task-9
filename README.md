TH task 9

# Password Generator

1. **Import Libraries:**
   - The script starts by importing the `string` and `random` libraries. `string` provides a collection of characters, and `random` is used for shuffling and generating random values.

2. **User Input:**
   - The `get_user_input` function is defined to get the desired length of the password from the user. It ensures that the input is a valid integer greater than or equal to 5.

3. **Generate Password:**
   - The `generate_password` function creates a strong password by using characters from lowercase letters, uppercase letters, digits, and punctuation.
   - The character sets are shuffled, and the password is constructed by taking a percentage of characters from each set based on the specified length.
   - `random.sample` is used to ensure that characters are unique within each set.
   - The final password is created by shuffling all the selected characters.

4. **Execution:**
   - The program then takes user input for the password length, generates the password, and prints the result.


# How to Use
   - Run the script.
   - Enter the desired length for your password when prompted.
   - The script will generate and display a strong password.
 

 # Code Structure:
 
   - `password_generator.py`: Main script containing the password generation logic.
   
# screenshots

![pa1](https://github.com/Srivarthaniselvam/TH-task-9/assets/151417502/b8c170eb-40b6-424a-bfc8-be4be3fe505a)
![pa2](https://github.com/Srivarthaniselvam/TH-task-9/assets/151417502/5a5f276e-27ec-4f23-a99e-a135ad7499b1)
![pa3](https://github.com/Srivarthaniselvam/TH-task-9/assets/151417502/014182e2-19b7-4ae5-9394-8633cf7caf58)
![pa4](https://github.com/Srivarthaniselvam/TH-task-9/assets/151417502/c8f83a29-58b7-422e-a1e8-f8da34987200)

# Build and Run Instructions:
    
    - Clone the repository.
    - Run the following command to generate a password:
      ```
      python password_generator.py
      ```
    

# Closing Statement:**
   
    ## Thanks for Using!
    Enjoy using the password generator to create secure and strong passwords.


13. **Commit and Push:**
    - Save your changes and commit them to your version control system (e.g., Git).
    - Push the changes to your GitHub repository.


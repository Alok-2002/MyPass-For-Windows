# MyPass Repository

MyPass is a simple password manager built using Python and the Tkinter library. It allows users to generate secure passwords, store them along with the corresponding website and email/username, view saved passwords, and update passwords if needed.

## Screenshots

![image](https://github.com/Alok-2002/SecureKeyGen/assets/93814546/e8db24e8-8184-4ea1-b516-ab76c4395bcc)


## Functionalities

### 1. Generate Password
- Clicking the "Generate Password" button will create a random strong password consisting of letters (both uppercase and lowercase), numbers, and symbols.
- The generated password will be copied to the clipboard automatically, making it convenient for users to use it immediately.

### 2. Store Password
- Users can enter the website, email/username, and password in the provided fields.
- Clicking the "Store Password" button will save the entered details to a file named "passwords.txt".
- Before saving, it will prompt the user to confirm whether they want to save the details.

### 3. View Saved Passwords
- To view saved passwords, the user needs to provide the master password (predefined as "password").
- Clicking the "View Saved Passwords" button will open a new window displaying all the saved passwords in a user-friendly format.
- The saved passwords are read from the "passwords.txt" file and displayed in the window.

### 4. Update Password
- Users can update the password for a specific website.
- They need to enter the website and the new password they want to use.
- Clicking the "Update Password" button will search for the website in the "passwords.txt" file and update the corresponding password.
- If the website is not found, it will show an appropriate message.

## How to Use
1. Clone the MyPass repository to your local machine.
2. Ensure you have Python 3.x and the necessary libraries (Tkinter, pyperclip) installed. You can install the required libraries using the following command:
   ```
   pip install tkinter pyperclip
   ```
3. Run the `mypass.py` file to launch the MyPass password manager. You can find this file in the root directory of the cloned repository.

## How to Clone the Repository
To clone the MyPass repository, follow these steps:
1. Open a terminal or command prompt on your local machine.
2. Change to the directory where you want to clone the repository.
3. Run the following command to clone the repository:
   ```
   git clone https://github.com/alok-2002/mypass.git
   ```


## Requirements
- Python 3.x
- Tkinter library (included in standard Python installation)
- pyperclip library (to copy generated passwords to the clipboard)

## Contribution
We welcome contributions to improve and enhance MyPass. If you'd like to contribute, follow these steps:
1. Fork the MyPass repository on GitHub.
2. Make the desired changes in your local fork.
3. Test your changes to ensure they work as expected.
4. Commit your changes with descriptive commit messages.
5. Push the changes to your fork.
6. Open a pull request to the main MyPass repository.

Please ensure that your contributions adhere to the project's coding standards and are well-documented.

## License
MyPass is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact Information
If you have any questions or need assistance with MyPass, you can contact us at:

- Email: [sharmaalok02gwl@gmail.com](mailto:sharmaalok02gwl@gmail.com)
- GitHub Repository: [https://github.com/alok-2002/mypass](https://github.com/alok-2002/mypass)

We hope you find MyPass helpful in managing your passwords. If you have any feedback or suggestions for improvement, feel free to open an issue or a pull request. Happy password managing!

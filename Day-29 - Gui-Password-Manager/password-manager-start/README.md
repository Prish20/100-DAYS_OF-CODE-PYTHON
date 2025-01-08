# Password Manager - Day 29 of 100 Days of Code

This project is a **GUI Password Manager** built using Python's `tkinter` library. It allows users to generate random passwords, save credentials securely, and manage password entries for various websites. This project is part of the 100 Days of Code challenge.

---

## Features

### 1. **Password Generator**

- Creates strong, random passwords consisting of:
  - Letters (uppercase and lowercase)
  - Numbers
  - Symbols
- Ensures password complexity by including a mix of all character types.
- Automatically copies the generated password to the clipboard using the `pyperclip` library.

### 2. **Credential Storage**

- Saves website name, email/username, and password entries to a file (`data.txt`) in the following format:
  ```
  Website | Email/Username | Password
  ```
- Ensures that no fields are left empty before saving.
- Prompts the user for confirmation before storing credentials.

### 3. **Graphical User Interface (GUI)**

- Simple and intuitive interface built with `tkinter`.
- Input fields and buttons for seamless interaction:
  - **Website**: Input for the website name.
  - **Email/Username**: Input for the email or username (pre-filled with a default email address).
  - **Password**: Field to input or auto-generate a password.
  - **Generate Password**: Button to generate a random password.
  - **Add**: Button to save the credentials.

---

## Installation

### Prerequisites

- Python 3.8+
- `pyperclip` library (for clipboard functionality)

### Steps

1. Clone the repository:
   ```
   git clone https://github.com/YourUsername/Prish20-100-DAYS_OF-CODE-PYTHON.git
   ```
2. Navigate to the project folder:
   ```
   cd Prish20-100-DAYS_OF-CODE-PYTHON/Day-29 - Gui-Password-Manager/password-manager-start
   ```
3. Install dependencies:
   ```
   pip install pyperclip
   ```
4. Run the application:
   ```
   python main.py
   ```

---

## Usage

1. **Launch the Application**:

   - Run `main.py` to open the password manager.

2. **Generate a Password**:

   - Click the **Generate Password** button to create a secure, random password.
   - The generated password will be automatically copied to your clipboard.

3. **Save Credentials**:

   - Enter the website name, email/username, and password.
   - Click the **Add** button to save the credentials to `data.txt`.

4. **Default Email**:

   - The email field is pre-filled with `adrian@gmail.com`. You can change this to your preferred email or username.

5. **File Location**:

   - All saved credentials are stored in `data.txt` in the same directory as `main.py`.

---

## File Structure

```
Prish20-100-DAYS_OF-CODE-PYTHON/
└── Day-29 - Gui-Password-Manager/
    └── password-manager-start/
        ├── README.md
        └── main.py
```

- **main.py**: The main application script.
- **README.md**: This file, containing details about the project.

---

## Screenshots

*Screenshot of the GUI Password Manager*

---

## Improvements

### Potential Enhancements:

1. **Error Handling**:

   - Handle missing `logo.png` to avoid crashes.

2. **Data Security**:

   - Encrypt the passwords before saving to `data.txt`.
   - Use a database for more secure storage.

3. **Data Retrieval**:

   - Add a feature to search and retrieve saved credentials by website name.

4. **Advanced Features**:

   - Allow editing or deleting saved credentials.
   - Add a "master password" to access the password manager.

5. **UI Enhancements**:

   - Use modern libraries (e.g., `tkinter.ttk`) for a polished interface.

6. **Input Validation**:

   - Validate email formats.

---

## Dependencies

- `tkinter`: Built into Python (for GUI).
- `pyperclip`: To copy passwords to the clipboard.

Install dependencies using:

```bash
pip install pyperclip
```

---

## License

This project is open-source and free to use under the MIT License.

---

## Acknowledgments

- **100 Days of Code**: This project is part of the Python 100 Days of Code challenge.
- **Angela Yu**: The project is inspired by the Day 29 challenge from Angela Yu's Python course.

---

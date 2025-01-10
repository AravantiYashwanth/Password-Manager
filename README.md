# Password Manager 🔐

A simple and intuitive **Password Manager** built using Python and Tkinter.  
This application helps users securely generate and save their passwords locally.

---

## Features 🚀
1. **Password Generator**: Create random and secure passwords with a mix of letters, symbols, and numbers.
2. **Clipboard Integration**: Automatically copy generated passwords for quick use.
3. **Data Management**: Save login details (Website, Email/Username, Password) in a local `data.json` file.
4. **User-Friendly GUI**: Intuitive interface powered by Tkinter.
5. **Password Retrieval**: Retrieve saved login details using the website name.

---

## How to Run 🖥️

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/password-manager-tkinter.git

2. Navigate to the project directory:
   ```bash
   cd password-manager-tkinter

3. Install the required dependencies:
   ```bash
   pip install pyperclip
4. Run the application:
   ```bash
   python main.py

## Usage 🛠️
1. **Generate Password**: Click on the "Generate Password" button to create a new password. The password will be copied to your clipboard automatically.

2. **Save Password**: Enter the website, email/username, and password, then click on the "Add" button to save the details to data.json

3. **Find Password**: Enter the website name and click on the "Search" button to retrieve the saved login details.

## Note 📝
- Ensure that data.json is in the same directory as main.py.
- If data.json does not exist, it will be created automatically when you save a password.
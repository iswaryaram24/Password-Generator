# Password-Generator
#  Secure Password Generator

A simple **GUI-based Password Generator** built using **Python and Tkinter**.
The application allows users to generate customizable passwords by selecting the desired password length and character types.

## Features

*  Set custom password length
*  Include uppercase letters (A-Z)
*  Include lowercase letters (a-z)
*  Include numbers (0-9)
*  Include symbols (!@#$)
*  Input validation for password length
*  Warning when no character type is selected
*  Simple and user-friendly GUI
*  Clean interface using Tkinter and ttk styling

##  Technologies Used

* **Python 3**
* **Tkinter** – GUI development
* **Random** – Password character selection
* **String** – Character sets and symbols

##  Project Structure

```text
Password-Generator/
│
├── password_generator.py
└── README.md
```

##  How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Password-Generator.git
```

### 2. Navigate to the project directory

```bash
cd Password-Generator
```

### 3. Run the application

```bash
python password_generator.py
```

The Password Generator window will open.

##  How It Works

1. Enter the required password length.
2. Select the character types you want to include.
3. Click **Generate Password**.
4. The generated password will be displayed in the output field.

##  Application Preview

Add a screenshot of your application here:

```text
![Password Generator Screenshot](screenshot.png)
```

##  Security Note

This project is designed for **learning and demonstration purposes**.

The current implementation uses Python's `random` module for password generation. For applications requiring **cryptographically secure passwords**, Python's `secrets` module should be used instead.

##  Learning Outcomes

Through this project, I practiced:

* Python GUI development with Tkinter
* Object-oriented programming
* Event-driven programming
* Input validation
* Working with Python libraries
* Building a simple user-friendly desktop application

##  Future Improvements

* Add a **Copy Password** button
* Add a **Password Strength Indicator**
* Add an option to **exclude ambiguous characters**
* Add **Show/Hide Password** functionality
* Use Python's `secrets` module for stronger password generation
* Add password history functionality



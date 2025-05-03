# **🔐 Password Strength Analyzer with Entropy Calculation**


This project is a Python-based utility that analyzes the strength of a user-provided password using entropy calculation, pattern detection, dictionary matching, and security recommendations. It also features a Graphical User Interface (GUI) built using Tkinter for user-friendly interaction.

🚀 Features
Entropy Calculation
Measures the randomness and complexity of the password to estimate its strength in bits.

Pattern Detection
Identifies weak patterns such as:

Repeated characters (e.g., "aaa")

Sequential numbers (e.g., "123")

Alphabetical sequences (e.g., "abc")

Dictionary Attack Simulation
Checks if the password exists in a predefined list of common or weak passwords (e.g., "123456", "qwerty").

Security Recommendations
Suggests how to strengthen weak passwords based on analysis results.

GUI with Tkinter
Interactive desktop interface with:

Password input field

Analyze button

Result display area for entropy, pattern matches, and recommendations

🧰 Technologies Used
Python 3

Tkinter (for GUI)

Regular Expressions (re)

Math Library

(Optional) numpy for advanced future functionalities

🛠️ How to Use
1. Clone this repository:
bash
Copy
Edit
git clone https://github.com/your-username/password-strength-analyzer.git
cd password-strength-analyzer
2. Run the Script
bash
Copy
Edit
python3 password_analyzer.py
⚠️ Ensure that Python 3 and Tkinter are installed. On Kali or Ubuntu, use:

bash
Copy
Edit
sudo apt update
sudo apt install python3 python3-tk
3. GUI Usage
Enter a password in the field.

Click the “Analyze Password” button.

Review the entropy value, detected weaknesses, and recommended improvements.

🧪 Example
Input: Brother@004
Output:

Entropy: 74.5 bits

Patterns: None

Recommendations: Your password is strong!

🔧 Future Enhancements
Use external wordlists like rockyou.txt for comprehensive dictionary checks

Estimate password cracking time based on entropy

Add graphical indicators (e.g., strength meters)

Create a web-based version using Flask or Django

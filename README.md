
Password Strength Checker
=========================

This is a simple Password Strength Checker web app built with Python (Flask), HTML, CSS, and JavaScript.
It evaluates password strength based on:

- Length
- Uppercase letters
- Lowercase letters
- Numbers
- Special characters

It returns a strength percentage and gives helpful feedback on how to make your password stronger.

---

Features
--------

- Score-based password evaluation (0–100%)
- Visual strength meter (color-coded)
- Live feedback on missing password elements
- Modern dark-themed UI

---

Requirements
------------

Make sure you have Python 3 installed, then install the required library:

    pip install Flask

Or use the requirements.txt:

    pip install -r requirements.txt

---

Project Structure
-----------------

password_checker/
├── app.py
├── requirements.txt
├── static/
│   └── style.css
└── templates/
    └── index.html

---

How to Run
----------

1. Clone or download the project.
2. Open a terminal in the project directory.
3. Run the Flask app:

       python app.py

4. Open your browser and go to:

       http://127.0.0.1:5000/

---

How It Works
------------

- The user enters a password.
- It is sent to the Flask backend.
- The backend analyzes the password:
  - Length
  - Uppercase/lowercase letters
  - Numbers
  - Special characters
- A score is calculated and converted to a percentage.
- The front-end displays a progress bar and suggestions.

---

To Do / Ideas
-------------

- Add real-time checking as the user types.
- Show/hide password toggle.
- Add emoji feedback.
- Save password history locally (optional).

---

License
-------

MIT License — free to use and modify.

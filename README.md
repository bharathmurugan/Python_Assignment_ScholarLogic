# 🐍 Python Fundamentals: Assignments & Practice

A collection of my Python coursework, from computer architecture basics to control flow, string handling and a small Flask web app. Most problems are framed around real business scenarios (Uber, AWS, Swiggy, Spotify, Duolingo, HDFC Bank) to build interview-ready problem solving.

**Author:** Bharath M, B.Tech Information Technology, Kongu Engineering College

---

## 📚 Assignments

| # | Assignment | Topics Covered |
|---|------------|----------------|
| 1 | **Computer Architecture & Python Foundations** | CPU vs GPU, binary and ASCII encoding, machine/assembly/high-level languages, compiler vs interpreter, platform independence |
| 2 | **Variables, Data Types & Basic Programs** | Naming rules, snake/Pascal/camel case, primitive vs non-primitive types, simple interest, average marks, GST calculation, variable swapping |
| 3 | **Input Processing & Type Casting** | Tuple unpacking (`a, b = b, a`), `input()`, `int()` casting, HackerRank-style raw stdin |
| 4 | **Operators & Conditional Control Flow** | Operator categories, `//` vs `/`, `**`, indentation rules, `if / elif / else`, `assert`, discount engine, SaaS usage billing |
| 5 | **Conditional Logic & Real-Time Business Systems** | Uber surge pricing, AWS auto scaling predictor, cloud SLA refund calculator, Swiggy weather advisory |
| 6 | **Loop Control, Strings, Indexing & Slicing** | `break`, `pass`, `while` loops, odd/even generators, positive/negative indexing, slicing, placement interview questions |
| 7 | **String Operations, Case Normalization & Web Integration** | Slicing engine, case-insensitive quiz with `.lower()`, ATM PIN retry and lockout logic, Flask routes |
| 8 | **Python Industry Engineering Assignment** | String parsing, conditional logic, dynamic pricing, inventory processing, authentication & lockout |

---

## 🧩 Assignment 8 – Python Industry Engineering

Assignment 8 focuses on applying Python programming concepts to real-world business and enterprise scenarios.

### Problems Covered

- **Netflix Streaming Session & Token Parsing**
  - String slicing and indexing
  - Region code extraction
  - Streaming quality extraction
  - Numeric content ID conversion
  - Token validation

- **Swiggy Dynamic Surge Pricing Engine**
  - Conditional branching
  - Boolean operators
  - Rain and peak-hour conditions
  - Dynamic delivery fee calculation

- **Amazon Inventory Alert & Auto-Restock System**
  - `for` loops
  - Inventory collection processing
  - Stock-level conditions
  - Restock counting
  - Critical and warning alerts

- **HDFC Bank Security Verification Guard**
  - `.strip()` and `.lower()`
  - Authentication validation
  - Attempt counter
  - Maximum 3 attempts
  - Account lockout logic

### Key Concepts

```text
String Indexing
String Slicing
Input Validation
Type Casting
if / elif / else
Boolean Operators
for Loops
while Loops
State Management
Authentication Logic
Security Lockout
🧩 Featured Mini Projects
Uber Surge Pricing Engine: applies a 2.5x fare multiplier only when rain, peak hours and low driver supply all hold.
AWS Auto Scaling Predictor: predicts total users from current load and growth rate, and decides whether to launch a new server.
Cloud SLA Refund Calculator: multi-branch if-elif-else refund tiers based on uptime.
Swiggy Weather Advisory System: conditional delivery advisories based on weather.
Supermarket Discount Engine: 10% discount on bills of ₹1000 or more.
SaaS Billing with Penalty Rule: CPU, storage and transfer charges plus a ₹500 penalty above 100 CPU hours.
Duolingo-style Geography Quiz: case-insensitive answer checking with .lower().
HDFC ATM PIN Lockout: retry limit and account lockout logic.
Netflix Session Token Parser: extracts region, quality and content ID from a structured session token.
Swiggy Dynamic Pricing System: calculates delivery charges based on weather, peak hours and order amount.
Amazon Inventory Alert System: identifies low-stock and out-of-stock products and calculates restock requirements.
HDFC Security Verification Guard: validates a passphrase with input normalization and account lockout logic.
Flask Web App: the quiz and ATM scripts served through / and /atm routes.
🛠️ Tech Stack
Language: Python 3
Web Framework: Flask (Assignment 7)
Core Concepts: String manipulation, indexing, slicing, type casting, conditional logic, Boolean operators, loops and input validation
Tools: Google Colab, VS Code, Git & GitHub Desktop
📁 Suggested Repository Structure
python-assignments/
├── assignment-1-computer-architecture/
├── assignment-2-variables-data-types/
├── assignment-3-input-type-casting/
├── assignment-4-operators-conditionals/
├── assignment-4b-business-logic-systems/
├── assignment-6-loops-strings-slicing/
├── assignment-7-strings-flask/
├── assignment-8-python-industry-engineering/
└── README.md
▶️ Getting Started
# Clone the repository
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

# Run any Python script
python path/to/script.py

# For the Flask app (Assignment 7)
pip install flask
python app.py

# Open the application
# http://127.0.0.1:5000/
🎯 Key Takeaways
Writing clean, readable control flow with correct indentation
Translating business rules into conditions and boundary-case tests (e.g. == 1000 vs > 1000)
Understanding string indexing and the n-1 stopping rule in slicing
Handling user input safely with type casting
Using .strip() and .lower() for normalized input validation
Processing collections using for loops
Managing repeated input using while loops
Building inventory monitoring and restock logic
Implementing basic authentication and security lockout logic
Extracting structured information using string indexing and slicing
Taking a terminal script and turning it into a web interface
📌 Status

Actively updated as new modules are completed.

Latest: Assignment 8 – Python Industry Engineering Assignment

📬 Connect

Feel free to open an issue or reach out if you have suggestions or feedback.

⭐ If you found this useful, consider giving the repo a star!

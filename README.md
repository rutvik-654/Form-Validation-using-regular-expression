# Form Validation using Regular Expressions 🧾✅

This Python project demonstrates **form validation** using **regular expressions (regex)**. It is designed to validate common user input fields such as name, email, phone number, and password with proper format checking.

## 🚀 Features

- 🔤 Validates names (no special characters, only letters)
- 📧 Checks for valid email format
- 📱 Validates phone numbers (10-digit, Indian format)
- 🔐 Enforces strong password rules (uppercase, lowercase, digits, symbols)
- 💡 Clean and simple Python logic using `re` module

## 🛠️ Technologies Used

- Python 3.x
- Regular Expressions (`re` module)

## 📂 Project Structure

Form-Validation-using-regular-expression/ │ ├── main.py # Core logic for form validation ├── validators.py # Individual field validation functions ├── test_cases.py # Sample inputs and edge case tests └── README.md # Project documentation

markdown
Copy
Edit

## 🧪 Validations Included

| Field      | Validation Criteria |
|------------|---------------------|
| **Name**   | Only alphabets, min 2 characters |
| **Email**  | Format like `example@domain.com` |
| **Phone**  | 10-digit Indian number starting with 6-9 |
| **Password** | Minimum 8 characters, includes uppercase, lowercase, digit, and symbol |

## 📌 Sample Regex Patterns

- **Email**: `^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$`
- **Phone**: `^[6-9]\d{9}$`
- **Password**: `^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)(?=.*[@$!%*#?&])[A-Za-z\d@$!#%*?&]{8,}$`

## ▶️ How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/Form-Validation-using-regular-expression.git
cd Form-Validation-using-regular-expression

# Run the validation script
python main.py

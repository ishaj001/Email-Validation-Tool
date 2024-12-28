
# Email Validation Tool

This project validates email addresses from a provided CSV file using the `email-validator` library. It checks if each email is valid and stores the validation results in a new CSV file. Invalid emails are flagged with error messages.

## Features
- Validates email addresses in bulk.
- Processes large files in chunks for efficient memory usage.
- Outputs a CSV file with validation status and error messages.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/your-username/Email-Validation-Tool.git
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Place your input CSV file (with columns `Mobile` and `Email`) in the project directory.
2. Run the script to validate emails:
   ```
   python validate_emails.py
   ```
3. The results will be saved in `Email_Base_With_Validation_Status_Opt_in_Yes.csv`.

## Dependencies
- pandas
- numpy
- email-validator

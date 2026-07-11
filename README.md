# 📧 Email Automation System using Python

A simple Python-based Email Automation System that allows users to send **single** or **bulk emails** with optional file attachments using Gmail SMTP.

## 🚀 Features

- 📩 Send emails to a single recipient
- 📧 Send bulk emails from a CSV file
- 📎 Attach one or multiple files
- 🔒 Secure email sending using Gmail SMTP with App Password
- 📝 Simple command-line interface
- ⚡ Easy to customize and extend

## 🛠️ Technologies Used

- Python 3
- smtplib
- csv
- os
- email (MIME)

## 📂 Project Structure

```
Email-Automation-System/
│── main.py              # Main program
│── emaillogic.py        # Email sending functions
│── emails.csv           # List of recipient email addresses
│── README.md
```

## ⚙️ How It Works

1. Enter the email subject.
2. Enter the email body.
3. Choose:
   - Send a Single Email
   - Send Bulk Emails
4. (Optional) Attach files.
5. Enter the recipient email or CSV file path.
6. The program sends the email(s) automatically.

## 📋 CSV Format

The CSV file should contain one email address per row.

Example:

```csv
abc@gmail.com
xyz@gmail.com
test@gmail.com
```

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Email-Automation-System.git
```

Go to the project folder:

```bash
cd Email-Automation-System
```

Run the project:

```bash
python main.py
```

## 🔐 Gmail Setup

To use Gmail SMTP:

1. Enable Two-Factor Authentication.
2. Generate a Gmail App Password.
3. Replace the following values in `emaillogic.py`:

```python
SENDER_EMAIL = "your_email@gmail.com"
SENDER_PASSWORD = "your_app_password"
```

> **Important:** Never upload your real email address or App Password to GitHub. Use environment variables or a `.env` file instead.

## 📌 Future Improvements

- Email templates (HTML)
- Schedule emails
- GUI using Tkinter
- Logging system
- Email status report
- Multiple CSV columns (Name, Email)
- Progress bar

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome.

## 📄 License

This project is open-source and available under the MIT License.

---

⭐ If you found this project useful, don't forget to star the repository!

# 🧾 bKash CLI Simulator (Python OOP Project)

This is a command-line simulation of the popular mobile wallet service **bKash**, developed using **Python and Object-Oriented Programming (OOP)** principles. The project mimics the real-life functionalities of a mobile money platform including sending money, cashing out, recharging mobile balance, donations, and PIN management.

## 🚀 Features

- ✅ Secure login with PIN validation
- 🔐 Account locking after 3 failed login attempts
- 💸 Send Money, Cash Out, Mobile Recharge, and Donations
- 📜 Full transaction logging with timestamps
- 📅 Daily transaction limit enforcement (25,000 Taka)
- 🔄 PIN change with confirmation
- 📊 View balance and transaction history
- 📥 Request money simulation
- 📟 Simple, interactive CLI (Command-Line Interface)

## 🛠️ Tech Stack

- Language: **Python 3**
- Paradigm: **Object-Oriented Programming (OOP)**
- Interface: **Command-Line Interface (CLI)**

## 🧩 Class Structure

### `Bkash` Class

| Method | Description |
|--------|-------------|
| `__init__()` | Initializes account with number, PIN, and balance |
| `validate_user()` | Authenticates user with lockout on failure |
| `validate_transaction()` | Checks for valid amount, balance, and daily limit |
| `log_transaction()` | Logs each transaction with type, amount, and timestamp |
| `send_money()` | Transfers money to another account |
| `cash_out()` | Withdraws cash (min 50 Taka) |
| `mobile_recharge()` | Recharges mobile (min 20 Taka) |
| `donation()` | Donates to a custom cause |
| `request_money()` | Simulates requesting money from another number |
| `change_pin()` | Allows PIN change with confirmation |
| `check_balance()` | Displays current balance |
| `view_transaction_history()` | Displays all past transactions |
| `my_bkash()` | Mini menu for PIN and transaction view |

## 🧪 How to Use

1. Clone the repo or copy the code into a Python file (e.g. `bkash_simulator.py`)
2. Run the script using:
   ```bash
   python bkash_simulator.py
   ```

## 🔑 Default Login

To get started, use the following default credentials:

- **Account Number:** `01712121212`
- **PIN:** `213`

Once logged in, follow the on-screen interactive menu to perform actions like sending money, checking balance, making donations, and more.

---

## 📌 Notes

- 🧍‍♂️ The program simulates a **single user account**.
- 📚 Designed purely for **educational and demonstration purposes**.
- 🚫 **No real transactions** are processed or connected to bKash.

---

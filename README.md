# Personal Assistant Toolkit (Python)

This project is a modular Python-based personal assistant that helps manage contacts, track birthdays, normalize phone numbers, and store data persistently using a custom file format.

## Features

### 📇 Contact Management (CLI Bot)
- Add, update, and view contacts
- Store multiple phone numbers per contact
- Error-handling with decorators
- Interactive command-line interface

### 🎂 Birthday Tracking
- Add and store birthdays
- Calculate days until next birthday
- Show upcoming birthdays (next 7 days)

### 💾 Persistent Storage
- Save and load records from a file (`records.txt`)
- Custom serialization format using `|`
- Context manager for safe read/write operations

### 📞 Phone Normalization
- Clean and standardize phone numbers
- Supports international Ukrainian format (+380)
- Removes unnecessary characters

---

## Project Structure

```txt
.
├── contact_bot.py        # CLI assistant bot (commands, contacts)
├── address_book.py       # OOP address book with records & birthdays
├── storage.py            # File save/load with custom protocol
├── phone_normalizer.py   # Phone number formatting utility
└── records.txt           # Saved data (auto-generated)

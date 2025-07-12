# WhatsApp Link Generator

This Python script automatically generates WhatsApp message links from a list of contact names and phone numbers in Excel or CSV format.

## 📌 Features
- Generates direct `wa.me` links with custom messages
- Supports bulk processing from Excel files
- Output saved in a new Excel file

## 🧰 Technologies Used
- Python
- pandas
- openpyxl
- re (Regex)

## 📝 Input Format
- Excel or CSV file with:
  - Column A: Name
  - Column B: Phone Number

## 📤 Output
- Excel with a new column: WhatsApp clickable link

## 🚀 How to Run
```bash
python wa_link_generator.py

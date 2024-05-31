# Email Data Extraction Project

## Overview
This project extracts specific data (name, phone number, email, company) from emails using Flask and IMAP, and stores the extracted data in a CSV file.

## Features
- **Email Extraction Endpoint**: Provides an API endpoint to extract data from emails.
- **IMAP Integration**: Supports multiple email providers (Gmail, one.com, outlook.com) using IMAP.
- **Data Extraction**: Uses regular expressions to extract structured data from email content.
- **CSV Export**: Saves the extracted data into a CSV file (`extracted_data.csv`).
- **Web Interface**: Basic HTML interface (`index.html`) for initiating email extraction.

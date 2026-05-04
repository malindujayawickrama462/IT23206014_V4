# IT23206014 - ITPM Assignment 01

## Project Description
This project is an automated test suite developed using **Python** and **Playwright**. It automates the process of testing the "Chat Translator" (Singlish to Sinhala) on the Pixels Suite website. The script reads test cases from an Excel file, performs the translation on the website, and writes the results back to the same Excel file.

## Prerequisites
Before running the script, ensure you have the following installed:
* Python 3.10 or higher
* Google Chrome Browser

## Setup & Installation

1. **Install Dependencies:**
   Open your terminal and run the following command to install the required libraries:
   ```bash
   pip install playwright openpyxl

   How to Run the Tests
Ensure your Excel file (IT23204898_Assignment_1.xlsx) is in the same directory as the script.

Make sure the Excel file is closed.

Run the following command in your terminal:

Bash
python test_automation.py --excel "IT23206014_Assignment_1.xlsx" --url "[https://www.pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator)" --wait-ms 5000 --save-every 1 --keep-open
Author
Registration Number: IT23206014

Module: IT3062 - Information Technology Project Management (ITPM)
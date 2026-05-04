# IT23697614 - Assignment 1: Singlish Transliteration Testing
## IT3040 - ITPM | BSc (Hons) in Information Technology


Repository Name: IT23697614_projectPlaywright
Repository Type: Public

STUDENT INFORMATION

Student Name: Bamunuarachchi R R
Registration Number: IT23697614
Course: IT3040 - ITPM
Assignment: Assignment 1 - Year 3 Semester 1
Option: Option 1 - Transliteration Accuracy Testing


## Automated testing of the Chat Sinhala transliteration function at https://www.pixelssuite.com/chat-translator using Playwright.

## Prerequisites
- Python 3.11 or 3.12
- Google Chrome

## Project Files
- `IT23697614_test_automation.py` - Playwright automation script
- `IT23697614_Test cases.xlsx` - Test cases with results

## Setup Instructions

### 1. Clone repo

bash
git clone https://github.com/Ravindu-Reshan/IT23697614_projectPlaywright.git

### 2. Dependencies run (one time)

bash
python -m pip install -U pip 
python -m pip install playwright openpyxl
python -m playwright install


## Running the Tests

python IT23697614_test_automation.py --excel "IT23697614_Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

## Test Results
- Total test cases: 50
- All test cases are negative (system failures)
- Status values: FAIL / UI Error


# ITPM-Assignment01-IT23681088_SECOND

### Setup Instructions

1. Install Python 3.13

2. Install dependencies:
   - pip install -U pip
   - pip install playwright openpyxl

3. Install Playwright browsers:
   - playwright install

4. Project setup:
   - Place the following files in the same folder:
     - test_automation.py
     - Assignment 1 - Test cases.xlsx

5. Open Command Prompt

6. Navigate to the project folder using cd:
   Example:
   - cd "C:\Users\User\Desktop\your-folder-name"

7. Run the script using the following command:

   python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

### Notes

- Make sure the Excel file name matches exactly
- Do not move the Excel file to another folder
- Keep both files in the same directory
- Press CTRL + C to stop the script after execution
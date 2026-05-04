📌 Overview

This project tests the accuracy of the Sinhala chat transliteration system: https://www.pixelssuite.com/chat-translator

The focus is on identifying cases where the system fails to correctly convert Singlish to Sinhala and automating the testing using Playwright.


⚙️ Setup & Installation

git clone https://github.com/randilkumal/IT23362826_ITPM_Assignment_1.git
cd IT23362826_ITPM_Assignment_1
pip install playwright openpyxl
playwright install


▶️ Run Tests

python test_automation.py --excel "test_automation/Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

📊 Test Case File

The Excel file in this repository:

#✔ Contains already executed test results (Pass/Fail)

✔ Includes Actual Output captured from the system

✔ Has two additional columns manually filled:

Singlish Input Types Covered
Evidence / Rationale

🔄 Updating Test Cases

If you need to modify or add test cases:

1.Update the Excel file:

test_automation/Assignment 1 - Test cases.xlsx2.Re-run the script using the command above to generate updated results.

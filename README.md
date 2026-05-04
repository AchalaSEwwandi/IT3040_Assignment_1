# IT23553514 - IT3040 Assignment 1

## Project Title
Automated Testing for Singlish to Sinhala Transliteration System

---

## Repository
https://github.com/AchalaSEwwandi/IT3040_Assignment_1.git

---

## Student Information
- **Student ID:** IT23553514
- **Name:** Sewwandi H.K.A
- **Module:** IT3040 - ITPM
- **Assignment:** Assignment 1 (Option 1)

---

## Project Structure

```
test_automation/
- test_automation.py                  → Playwright automation script
- Assignment 1 - Test cases (3).xlsx  → Excel file with test cases & results
- README.md                           → Project documentation
```

---

## Technologies Used
- Python 3.11/3.12
- Playwright (UI Automation)
- OpenPyXL (Excel handling)

---

## How to Install Dependencies

```
pip install playwright openpyxl
playwright install
```

---

## How to Run Tests

```
python test_automation.py --excel "Assignment 1 - Test cases (3).xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 8000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```

---

## Important Notes
- This system uses strict comparison
- Even small differences in Sinhala output (spacing, formatting, spelling) will result in FAIL
- Some failures are expected due to:
  - Transliteration inconsistencies
  - Mixed language complexity
  - UI timing delays

---

## Final Status
- Automation script working
- Excel-based validation completed
- Test coverage includes all 24 Singlish input types
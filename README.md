IT23411562 - ITPM(IT3040) Assignment 1

Singlish automated testing using Playwright

Repository link - https://github.com/manulbp/SinglishTesting_2.git

Tools & Technologies utilized:
- Python
- Playwright
- OpenPyxl

File structure
- IT23411562_Assignment 1 - Test cases (Contains neagtive test cases)
- test_automation.py (Playwright automation script)
- IT23411562_github_repo_link (Repo link)
- README.md (Project documentation)

A simple guide to run the project
- Open terminal inside project folder using cmd
- Install dependencies
  pip install -U pip
  pip install playwright openpyxl
  playwright install
-Run the command
  py -3.12 test_automation.py --excel "IT23411562_Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

Output
-Actual result of each scenario with the respective status(Fail/Pass) will be auto-updated.(two columns)

Test case information
- 50 Negative test case scenarios
 




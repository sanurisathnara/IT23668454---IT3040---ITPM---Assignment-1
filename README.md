\# IT3040 - ITPM Assignment 1

Option 1: Transliteration Accuracy Testing (for students familiar with Sinhala)



\## Prerequisites

\- Python 3.11 or 3.12

\- Google Chrome



\## Installation

1\. Navigate to the `test\_automation` folder.

2\. Run the following commands:

&#x20; ```bash

&#x20;  pip install -U pip

&#x20;  pip install playwright openpyxl

&#x20;  playwright install



\##Test Run

From the test\_automation folder, execute:



python test\_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open



\##Test Results

* Total test cases: 50
* All test cases FAIL (negative testing)
* All 24 Singlish input types from Appendix 1 are covered.





\##Author

IT23668454 - Karunadeera A.N.S.S



\##Git Repository

https://github.com/sanurisathnara/IT23668454---IT3040---ITPM---Assignment-1.git


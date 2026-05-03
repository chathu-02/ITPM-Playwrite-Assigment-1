Playwright Automation - Transliteration Accuracy Testing

    
  This project contains automated test cases to evaluate the transliteration accuracy of the Chat Sinhala function available at 
                      Pixels Suite Chat Translator.  
  
  Project Overview
  
  The objective is to identify and automate 50 scenarios where the system fails to correctly convert informal "Singlish" input into the corresponding Sinhala output. The test suite covers 24 distinct Singlish input types as specified in the assignment guidelines. 
  Prerequisites
Before running the tests, ensure you have the following installed:Node.js (v16 or higher)npm (comes with Node.js)Installation InstructionsClone the repository:Bashgit clone 
Navigate to the project folder:Bashcd 
Install dependencies:  Bashnpm install
Install Playwright Browsers:Bashnpx playwright install
Running the TestsTo execute all the automated test cases and generate results, use the following command:  Bashnpx playwright test
Viewing ResultsOnce the execution is complete, the results are recorded in the provided Excel file: "Assignment 1 - Test cases".  For a detailed Playwright HTML report, run:Bashnpx playwright show-report

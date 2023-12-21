# Grade detail checker

- This application allows users to upload a CSV file with academic records or read it from their Google Drive. 
- It features a column named "PW," which serves as a passcode, enabling individual students to access their detailed academic records on their devices. 
- This PW is a unique code known only to each student and must be pre-recorded in the CSV file. 
- The file should contain this PW column with passcodes comprising numbers, letters, or a combination of both. 
- Other columns in the file should include student grades for various assessments like attendance and midterms. 

For instance, your csv file should look like this:

|Name|ID|..|PW|..|Grade|
|--|--|--|--|--|--|
|Mary|20232123|...|ZB234k|...|B+|

Using a live app, your student will type PW. Then the output displays:

|Name|Mary|
|--|--|
|ID|2023212|
|...|...|
|Grade|B+|

**Key notes:** 
1) Students must know their passcode.
2) 2) The application uses Gradio to create a live link, which the administrator informs students about within a specific time frame. (This link remains active for 72 hours.)

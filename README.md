## Student Percentage Calculator
A Python-based utility designed to automate the calculation of student academic performance. This application simplifies the process of aggregating marks from multiple subjects and generating a final percentage and performance status.
## Features
* Multi-Subject Entry: Allows users to input marks for a variable number of subjects.
* Percentage Calculation: Automatically computes the total score and the corresponding percentage.
* Grade/Status Evaluation: Basic logic to determine if a student has met the passing threshold.
* Dynamic Input: Uses interactive console prompts for a customized user experience.
## Technical Implementation
* List Handling: Efficiently storing subject marks for batch processing.
* Mathematical Operations: Implementing formulas for total sum and percentage calculation 
($Percentage = \frac{Obtained Marks}{Total Marks} \times 100$).
* F-Strings: Utilizing formatted string literals for clean and readable output.
* Input Validation: Ensuring that the entered marks are within valid numerical ranges.
## Installation & Usage
### Prerequisites
* Python 3.x installed. Check your version with:
```Bash```
python --version
```Bash```
### Running the Script
1. Clone the repository:
```Bash```
git clone https://github.com/Haniatahir05/studentpercentage.py.git
```Bash```
2. Navigate to the folder:
```Bash```
cd studentpercentage.py
```Bash```
3. Run the application:
```Bash```
python studentpercentage.py
```Bash```
## Sample Workflow
1. The script prompts for the student's name and the number of subjects.
2. The user enters the marks obtained in each subject.
3. The system calculates the total out of the maximum possible marks.
4. The final percentage and performance summary are displayed on the console.
## Future Enhancements
* Exporting results to a .csv or .pdf report.
* Adding a graphical interface using CustomTkinter.
*Implementing support for weighted averages based on subject credit hours.

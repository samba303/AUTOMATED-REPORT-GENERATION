# AUTOMATED-REPORT-GENERATION
![logo_ironhack_blue 7]

# Lab | Macros Automated Report Generation

- In this lab, you will use the file `deduction_import_raw.xlsx`. The file is provided in the folder `files_for_lab`. This is the raw data file that is imported from the server.

### Scenario

The payroll team in your company receives information from your client in a specific format. The payroll team then needs to manipulate the information in a format that can be uploaded into the payroll processing software directly. The software can only read the information in a specific format. Your task is to automate this process that will save a lot of time for the payroll team and make the process more robust.

Here is a snapshot of what the initial format of the file given to the payroll team looks like: [link to the image - Raw data format in excl]
Here is how the final output should look like: [link to the image - Final output]
### Instructions

- No headers are required.
- The first column consists of SSNs without the hyphens
- The second column consists of a constant value `EE_DDUCT`
- Third column consists of values from the column AG ie `Benefit`. We would only need the first three letters from this column (if there's value in that column that is more than three letters)
- Fourth column consists of the numerical value from the column `EE Cost` followed by `|` (vertical bar repeated six times)

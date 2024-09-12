# Exercise-4 Read and Write Excel Data

### Reg No : 212221040020


## AIM: 
 To create a workflow in UiPath that reads data from an Excel file and writes the same data into another Excel file.
 
## Activites Required:

1.Excel Application Scope: Opens the Excel file to read or write data.
2.Read Range: Reads data from an Excel sheet and stores it in a DataTable.
3.Write Range: Writes data from a DataTable into another Excel sheet.

## Procedure:
  1. Start a Process naming "Excel" with a description.
  2. Open the main sequence.
  3. Read Data from Source Excel File and drag the Excel Application Scope activity to the designer panel.
  4. In the File Path property, select the source Excel file.
  5. Drag the Read Range activity inside the Excel Application Scope.
  6. Set the SheetName as "Sheet1" from which you want to read the data.
  7. Leave the Range field empty to read the entire sheet.
  8. Store the result in a DataTable variable .
  9. Drag another Excel Application Scope activity below the previous one.
  10. In the File Path property, provide the target Excel file.
  11. Drag the Write Range activity inside the second Excel Application Scope
  12. Set the SheetName where you want to write the data
  13. Set the SheetName  where you want to write the data
  14. Set the starting cell (e.g., "A1") where the data will be written.
  15. Make sure to check the Add Headers option if you want column headers in the target Excel file.
  16. Save and Run the Project
## Workflow:
![image](https://github.com/user-attachments/assets/4ba2ee0f-a6ff-4159-9617-016c8cc3902f)


## Output:
![image](https://github.com/user-attachments/assets/29a81690-8471-46d7-a41b-6b5555fe70e2)


## Result:
  Thus, the workflowthat reads data from an Excel file and writes the same data into another Excel file is implemented successfully.
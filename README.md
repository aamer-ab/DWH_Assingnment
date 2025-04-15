# DWH_Assingnment

This repository contains the implementation of **Task 1** of the Data Warehouse project using SQL Server Integration Services (SSIS).

## Contents

- Load data from JSON file (converted to Flat File)
- Transfer data to SQL Server using OLE DB
- Create a table named `University` with the following fields:
  - `ID`: Identity number
  - `Name`: University name
  - `Country`: Country name
  - `Alpha_Two_Code`: Country code (2 letters)

## Tools Used

- Visual Studio 2022
- SQL Server Management Studio (SSMS)
- Integration Services Extension
- GitHub Desktop

## Execution Steps

1. Open the project in Visual Studio.
2. Go to **Control Flow** tab.
3. Click `Start` to run the package.
4. After success, open SSMS and run:
   ```sql
   USE DWH2025;
   SELECT * FROM University;




   Notes
Make sure the OLE DB server name matches your local instance 

If you're using SQL Authentication, update the connection settings accordingly.

yaml
نسخ
تحرير


 

# SAP ABAP Sales ALV Report

## Project Title

Custom Sales Document ALV Report using SAP ABAP

## Project Description

This project demonstrates the development of a Custom ALV (ABAP List Viewer) Report using SAP ABAP programming.

The report retrieves sales document details from the SAP database table VBAK and displays the results in an ALV Grid format. It shows important information such as Sales Document Number, Created Date, and Created By.

A custom field catalog is used to define meaningful column headings, making the report organized and easy to understand.

The ALV report provides interactive features such as:

- Column sorting
- Data filtering
- Structured tabular display
- Custom column headings
- Improved readability of sales document data

## Tools and Technologies Used

- SAP S/4HANA
- SAP ABAP Programming Language
- SE38 – ABAP Editor
- ALV Grid Display
- SAP Data Dictionary (SE11)
- Function Module: `REUSE_ALV_GRID_DISPLAY`

## Tables Used

**VBAK – Sales Document Header Data**

The report uses the following fields from VBAK:

- `VBELN` – Sales Document Number
- `ERDAT` – Date on Which the Record Was Created
- `ERNAM` – Name of the Person Who Created the Record

## Project Objective

The objective of this project is to demonstrate the practical implementation of SAP ABAP reporting concepts, including:

- Retrieving data using the `SELECT` statement
- Declaring and using internal tables and work areas
- Creating a custom ALV field catalog
- Defining user-friendly column headings
- Displaying sales document data using ALV Grid
- Understanding basic SAP table access and report development

## Project Output

The report displays sales document records in an ALV Grid with three columns:

1. Sales Document
2. Created Date
3. Created By

The output provides a clear and structured view of sales document header information in SAP.

## Author

Aman Khillare

## Course

SAP ABAP Development / SAP S/4HANA

## Institution

Sanjivani College of Engineering, Kopargaon

## Repository Contents

- `ZSALES_ALV_REPORT.abap` – ABAP report source code
- `sales-alv-report-output.png` – Screenshot of the ALV report output

## Key Learning Outcomes

- Understanding SAP ABAP report development
- Working with the VBAK database table
- Implementing ALV Grid display
- Defining custom field catalogs
- Presenting SAP data in a readable tabular format

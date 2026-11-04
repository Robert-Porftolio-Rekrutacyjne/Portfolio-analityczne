Add Mark 7 operations dataset and Powe Query transformation

Mark 7 - Operational Analytics
This project focuses on data preparation and quality improvement using Microsoft Excel and Power Query.
The objective was to transform a synthetic operational dataset into a consistent and structured data model suitable for further business analysis.

The dataset contains 720 operational records covering 2028, supported by therr reference tables: dept., process, employees.

TOOLS
- Microsoft Excel
- Power Query

PROJECT SCOPE
The project includes:
- Data type standardization and format correction.
- Text cleaning and normalization.
- Duplicate detection and removal.
- Correction of inconsistent indentification keys.
- Handling missing and invalid values.
- Median-based imputation of selected numerical fields.
- Data consistency and quality checks.

DATA STRUCTURED
The workbook contains:
- TabelaOperacjeRaw - original operational data
- Tab_Operacje - cleaned operational data
- Tab_Słownik_Działów - dept. reference table
- Tab_Słownik_Pracowników - employee reference table
- Tab_Słownik_Procesów - process reference table
- Instrukcja
- Dokumentacja_Czyszczenia - documentation of the data preparation process.

Data quality approach
Data cleaning was performed using explicit transformation rules. Missing and invalid values were handled according to the defined business rules rather than by indiscriminate row removal.
Median imputation was used for selected numerical fields, taking into account and revelant dept. and process or dept. grouping.
Original source queries were preserved separately from the cleaned queries to maintain transparency and allow comparision.

OUTCOME
The result is a structural and cleaned operational dataset prepared for further analysis, reporting and business intelligence application.

Note: The dataser is asysthetic and was created for learning and portfolio purposes.

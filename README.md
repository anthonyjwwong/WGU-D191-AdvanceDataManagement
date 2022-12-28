# WGU-D191-AdvanceDataManagement

Plan for and compose the sections of a real-world business report that can be created from the DVD Database on Labs on Demand (see link below), and demonstrate the functionality of the supporting SQL code by doing the following:

**A.**<br /> 
Summarize one real-world business report that can be created from the attached Data Sets and Associated Dictionaries.

Describe the data used for the report.

Identify two or more specific tables from the given dataset that will provide the data necessary for the detailed and the summary sections of the report.

Identify the specific fields that will be included in the detailed and the summary sections of the report.

Identify one field in the detailed section that will require a custom transformation and explain why it should be transformed. For example, you might translate a field with a value of ‘N’ to ‘No’ and ‘Y’ to ‘Yes’.

Explain the different business uses of the detailed and the summary sections of the report.

Explain how frequently your report should be refreshed to remain relevant to stakeholders.

**B.** <br /> 
Write a SQL code that creates the tables to hold your report sections.

**C.** <br /> 
Write a SQL query that will extract the raw data needed for the Detailed section of your report from the source database and verify the data’s accuracy.

**D.** <br /> 
Write code for function(s) that perform the transformation(s) you identified in part A1.

**E.**<br /> 
Write a SQL code that creates a trigger on the detailed table of the report that will continually update the summary table as data is added to the detailed table.

**F.** <br /> 
Create a stored procedure that can be used to refresh the data in both your detailed and summary tables. The procedure should clear the contents of the detailed and summary tables and perform the ETL load process from part C and include comments that identify how often the stored procedure should be executed.

Explain how the stored procedure can be run on a schedule to ensure data freshness.

**G.** <br /> 
Provide a Panopto video recording that includes a demonstration of the functionality of the code used for the analysis and a summary of the programming environment.


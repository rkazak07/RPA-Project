# Uipath Rpa Excell File Comprarison

### Overview

In this uipath automation, it compares the sheets in an excel with each other and finds the same names and lists them in a different sheet.


### How to use

* Download Uipath windows
* Install the excel you want to compare to the Data folder
* Edit Excell_sheet_compare_config\Config/config.xlsx
* Run project

###  Config.xlsx Parameters

| Parameter | Description | Default
| ------ | ------ | ------ |
| `ORCHESTRATOR_QUEUE_NAME` | Orchestrator queue Name. The value must match with the queue name defined on Orchestrator.|Q1_DUMMY|
| `logF_BusinessProcessName` | Logging field which allows grouping of log data of two or more subprocesses under the same business process name|Framework|
| `MainPath` | Data file Location |C:\Users\myuser\Documents\UiPath\Data\|
| `ExcelDefaulName` | Excel file ExcelDefaulName_date.xlsx |my_project|
| `SeperateFile` | If it writes ON, it creates an external report file. If it writes OFF, it overwrites the existing File. |OFF|
| `ReportPath` | " " |C:\Users\myuser\Documents\Excell_sheet_compare\EndReport\|
| `ExcelReportName` | " " |my_project_report|
| `ManualFileControl` | If ON is written, it controls what is given. Off writers check the religion and format when the standard should not come. |ON|
| `ManualFilePath` | the directory where the work will be performed |C:\Users\myuser\Documents\UiPath\Data\my_project_date.xlsx|
| `strReplaceClear` | extension that will not scan within the scan |.domain.com|
|`TempExcelFile` | Used for one-to-one matching 2. excel is deleted when the process is completed. |False|

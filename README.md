## To modify:

1. Change 2 files names:
   * Data/Config\_Process\_Name\_Dispatcher.xlsx
   * Tests/TS\_Process\_Name\_Dispatcher.xlsx
2. In 3 Workflows change 2 variables:
   * Initialization/Init Configs
   * \_Sandbox/Init Configs
   * TC\_WorkflowName/Init Configs
     * Assign - strConfigFilePathLocal
     * Get Asset - strConfigFilePath
* Edit process: name, description, author here and in project.json
* Edit Main Workflow properties name
* Edit Config values and move file to another directory if needed
* Edit Project Settings
* Add assets to Orchestrator if needed
* Add Queue to Orchestrator
* Re-add test data Excel file, to TC workflows if needed
* Update packages if needed
* Open each file \& Workflow for error check
* Remove unused imports
* Remove unused Workflows
* Remove unnecessary Then-Else sequences
* Remove unused entries in Config
* Remove marked in yellow Settings \& Constants entries in Config
* Run analyzer
* Run parse XAML

## Delete if not used:

##### Activities\\Workflows <> Files <> Config entries

* Build Data Table - dtExcelReportTable <> <>
* TC\_WorkflowName.xaml <> TS\_Process\_Name.xlsx <>
* AppXYLogin.xaml <> <> AppXYLogin
* AppXYLogout.xaml <> <>
* ExcelGetTable.xaml <> Input\_File.xlsx <> ExcelInputFilePath, ExcelInputSheet, RequiredColumnNames, ExcelGetTable
* OutlookGetEmails.xaml <> <> OutlookInboxFolderPath, OutlookEmailsAmount, OutlookGetEmails
* OutlookMoveEmail.xaml <> <> OutlookInboxFolderPath, OutlookEmailsAmount, OutlookGetEmails
* APIRunQuery.xaml <> <> APIRunQuery
* FoldersCreate.xaml <> <>
* QueueGetAllItems.xaml <> <>
* ShowRobotStatus.xaml <> Robot\_Zakończył\_Pracę.txt <> RobotStatusFolderPath, ShowRobotStatus
* SQLRunQuery.xaml <> <> SQLRunQuery

##
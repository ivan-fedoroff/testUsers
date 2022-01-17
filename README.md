## testUsers
test service Users (http://users.bugred.ru/) by Olga Nasina
WSDL — http://users.bugred.ru/tasks/soap/WrapperSoapServer.php?wsdl (SOAP)
##### Testing doRegister (soap via SOAPUI). Check-list: https://docs.google.com/spreadsheets/d/1MKe6Xqifjws4tp1I8SzYPsy9GvLacvi-8eQ3lcvErZk/edit?usp=sharing
- add WSDL to SOAPUI
- import testsuite TestSuite-doRegister.xml 
- import testsuite Library.xml to make reports to csv file (if you work in Windows, change all '/' in paths definitions to '\\' in library/Reporting_Utility/Test_Steps/GenerateCSVReport)
- run test

To run this project:
1) Dowload the entire project folder without altering the folder structure.
2) Open the 'project.json' file in UIPath Studio and install PDF Dependencies if not already installed.
3) Run the main.xaml file.
4) Emails will be sent to all the students whose payment invoiced are present in the 'Invoice Samples' folder.

To add a new invoice to be processed:
1) Use the 'invoice example.docx' file and create a new invoice pdf. 
2) Add the invoice to the 'Invoice Samples' Folder and update the 'Student Database.xlsx' file with Name, USN and Mail Id.

Note: All adressing is relative to the following project structure
RPA AAT Project
 |
 |  |-- .entities
 |  |-- .settings
 |  |-- Invoice Samples
 |  |    |-- invoice_example_1.pdf
 |  |    |-- invoice_example_2.pdf
 |  |    |-- invoice_example_3.pdf
 |  |    |-- invoice_example_4.pdf
 |  |    |-- invoice_example_5.pdf
 |  |    |-- invoice_example_6.pdf
 |  |-- Email_Template.txt
 |  |-- expressions.txt
 |  |-- invoice example.docx
 |  |-- main.xaml
 |  |-- project.json
 |  |-- readme.txt
 |  |-- Student Database.xlsx
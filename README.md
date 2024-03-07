# Leave-Management-System
Developed a ServiceNow Application for Employee Leave Management System.

**Business Requirement**
1. HR business has a requirement to create a new application in SN which will be a global application for submitting leave request by employees and maintaining leave data of employees.
2. The app should have configuration option to define the leaves for different country. It should be a global application.

Tables -
Leave request
Leave logic - calculator - static
Leave bucket - balance - dynamic
Front end - Portal Request Form - record producer

Step1 : Create the application.  
Step 2 : Create Tables - Add fields - Add Choices - Pull choices from other table - advance view.  
Step 3 : Form Design.  
Step 4 : Create Business Rules.  
Step 5 : Write UI Policies.  
Step 6 : Calculation - using script includes and scripting - Write client scripts , Write a server side to calculate the duration and pull that into the client side.  
Step 7 : Write client scripts to calculate and set the duration as per half day.  
Step 8 : Wrote client scripts and UI policies and actions to change the form - mandatory, read only.  
Step 9 : Populating Data from server side on the client side - populating the duration, accrued , leave taken and balance fields automatically.  
Step 10 - To calculate the leaves of each user.  
Step 11 - To give leave approvals for an employee by the manager using flow designer.  




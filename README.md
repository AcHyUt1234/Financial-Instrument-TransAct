# Financial-Instrument-TransAct

Guide to Install and run on your system:
- Download and install Code::Blocks IDE on the machine from here: https://bit.ly/2Vlkvu2
- Files needed to be included in the lib folder of Code::Blocks for graphics support can be downloaded from here: https://bit.ly/3lokuQP
- Copy and Paste the graphics.h and winbgim.h files into include folder of Code::Blocks directory to this path: C:\Program Files (x86)\CodeBlocks\MinGW\include
- Copy and paste libbgi.a file in the lib folder of Code:Blocks to this path: C:\Program Files (x86)\CodeBlocks\MinGW\lib
- For additional compiler settings, refer: https://bit.ly/3lokuQP
- To simply execute the project application, follow the trajectory: bin > Debug > BM in the Project documentation

Software instructions:
The main menu has 4 options:
1. New account : If the user wishes to create a new account, select this option and provide valid details as asked by the system. If details are valid, a new account will get created.

2. Pre-existing account : If the user already has an account, he/she can log in using a valid account number and pin. If done successfully, the following menu will appear
a). Deposit amount
b). Withdraw amount
c). Balance enquiry
d). Close an account
e). Pin change
f). Transfer account
g). Exit

3. Admin account : This is a special account and authorities with a specific ID and PIN can log in into this account. This has the following functionalities.
a). Complete account holder list
b). Deposit cash
c). Withdraw cash
d). Check available balance
e). Exit

Admin can only deposit upto the range of 1 lac (At any point in time, machine cannot possess more than 1 lakh; transaction won't go through if this limit is crossed)

Note: 
1. Digits in account number should be between 8 and 16
2. System can’t have duplicate account numbers.
3. Pin has to be a 4 digit number.

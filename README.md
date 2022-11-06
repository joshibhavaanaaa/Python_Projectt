# Python MySQL Project
I have developed this project "SuperMarket Billing System" using MySQL and Python.
The database of this project is stored in MySQL tables and its front-end is developed in Python CUI ie for all operations you have to type the necessory options.

# Basic information of SuperMarket Billing System Project:
Front End  : Python 3.10
BackEnd   : MySQL

# MySQL Table Structure of SuperMarket Billing System Project:
Whole Database is divided and stored in four main tables, they are login, Items, Bills, and Transaction. Detailed description and sample records are as follows:

# Login table contains the user’s Name and password that is used to authenticate the user of the system.
Table 1>  login;
Field      Type         Null    Key     Default              
id        int(11)       NO      PRI       NULL       
name      char(30)      YES               NULL                  
pwd       char(30)      YES               NULL 
* 3 rows in set....

# Items tables contains items details available in the super store.
Table 2>  items;
Field         Type        Null    Key    Default             
id           int(11)      NO     PRI     NULL    
item_name    char(30)     YES            NULL                    
price        float(8,2)   YES            NULL  
* 3 rows in set....

# Bills table contains the bill information along with its customer.
Table 3> bills;
Field        Type       Null    Key    Default   
bill_id     int(11)     NO      PRI     NULL    
name        char(30)    YES             NULL    
phone       char(15)    YES             NULL                   
bill_date   date        YES             NULL
* 4 rows in set....

# Transaction table contains the bill Id and the items purchased aginst that bills.
Table 4> transaction;
Field      Type      Null    Key    Default
id        int(11)    NO      PRI    NULL 
item_id   int(11)    YES            NULL
qty       int(11)    YES            NULL
bill_id   int(11)    YES            NULL
* 4 rows in set....

# How bill is generated:
The bill consits the name, the email id and the phone number of the supermarket. 
Later, in the bill the date is generated at the time of purchase, the name, the phone number of the customer and bill no is created.
However, the bill has the list of items, the quantities, price and amount purchased by the customer.
Finally on the end it displays the total payable amount of the items purchased by the customer.
Further if we need to purchase some more items after the bill generation we can still press any key to continue/goahead.

# Final Conclusion On SuperMarket Billing System:
This project has taken the real world scanario thus the same can be implement on restourant and food court to generate thier billing system.
If you want to learn the project development in python then this project can give you a real insight.
Though all care has been taken while developing this project but if you are able to find any bug in this system then that is mine. 
Source code is totally yours. Use it as you want.

                                                                                                                       END...












### 1) What is data, database and a DBMS?

Storing data and retrieving information is the key for businesses to run efficiently. The term data can be defined as 
facts about something or someone. 
For example, data can be anything such as name of a person, number or images, video etc. 

When the data is converted to meaningful and useful form then it is called as information. 
A database can be defined as a collection of related data from which users can efficiently retrieve the desired information.
Computer databases have replaced tons of paper,file folders and ledgers as the primary media to store all information.
Thus, the collection of data, usually referred to as the database, contains information relevant to an enterprise or business.

A database-management system (DBMS) is an integrated set of programs used to create,access and maintain a database.

The primary goal of a DBMS is to provide a way to define, store,manipulating and retrieving database information that is
both convenient and efficient.

Database systems are designed to manage large bodies of information. Management of data involves both
defining structures for storage of information and providing mechanisms for the manipulation of information.
In addition, the database system must ensure the safety of the information stored, despite system
crashes or attempts at unauthorized access. If data are to be shared among several
users, the system must avoid possible anomalous results.

Thus the database and the DBMS software are collectively called as Database systems.

### 2) What are some applications of DBMS?

Databases are widely used. Here are some applications:

a) Sales: For customer, product, and purchase information.

b) Accounting: For payments, receipts, account balances, assets and other accounting information.

c) Human resources: For information about employees, salaries, payroll taxes, and benefits, and for generation of salary checks.

d) Manufacturing: For management of the supply chain and for tracking production of items in factories,
inventories of items in warehouses and stores, and orders for items.

e) Online retailers: For sales data , online order tracking, generation of recommendation lists,
and maintenance of online product evaluations.
 
f) Banking: For customer information, customer inquiries, accounts, loans, and banking transactions.

g) Credit card transactions: For purchases on credit cards and generation of monthly statements.

h) Finance: For storing information about holdings, sales, and purchases of financial instruments such as stocks
and bonds; also for storing real-time market data to enable online trading by customers and automated trading
by the firm.

i) Airlines and Railways : They use databases for reservations and displaying schedule information.

j) Education : Schools,colleges and universities use DBMS for student information, course registrations, and grades.

k) Telecommunication: For keeping records of calls made, generating monthly bills, maintaining balances
on prepaid calling cards, and storing information about the communication networks.


### 3) What are the disadvantages of file-processing systems ?

In file-processing systems, data is stored in files and then programmers write programs to add,modify,delete and 
retrieve information from these files.
Consider a bookstore that uses a file processing system to keep track of all the available books. The system maintains a file named BOOK to store information 
related to the books. This information includes ISBN,book title, price, year of publishing,copyright data,category,number of pages,name of author, name of 
publisher,address of publisher etc.
The system also provides many programs to allow users to manipulate information stored in BOOK file. For example, the system may contain programs to add 
information about a new book, modify any existing book information and print the details of books according to the categories.

Suppose, a need arises to keep additional information about the publishers of the books that includes phone number and email. To satisfy this 
requirement, the system creates a new file PUBLISHER, which included name, address, phone number and email id of publishers. New application programs are
written to manipulate information in the PUBLISHER file. 
Thus, with increasing and changing requirements as the business grows, new files keep getting added all the time.

But this file-processing system creates problems listed below:

1) Same information can be duplicated in many files. For example, the name and the address of publisher are stored in BOOK file as well as in PUBLISHER file.
   This duplication of data is called data redundancy which leads to storage space wastage. Data redundancy also causes data inconsistency. 
   To understand this let us consider an example. Suppose the address of the publisher is changed. Now we need to update both BOOK file and PUBLISHER file with this 
   new address. But if the BOOK file address is not updated due to a programming anomaly then the same publisher will have two different addresses in two different files 
   leading to data inconsistencies.
2) In almost all applications, there are certain rules or constraints that need to be fulfilled at all times. These are called as data integrity rules.
   In file processing systems, these rules need to be programmed in all the concerned files. If a particular constraint changes then all the affected files need to be 
   explicitly changed.
3) File-processing systems lack security features as programs can be added haphazardly.
4) Problems can mount if programs are written in many programming languages leading to confusion.

### 4) What are the advantages of DBMS systems ?

1) Centralised data management: In the database approach, the data is stored in a central location and is shared among multiple users.
2) Controlled data redundancy: During database design, various files are integrated and each logical data item is stored at central location. This eliminates 
   replicating the data item in different files that ensures consistency. It also saves storage space.  
3) Enforcing data integrity: Various data integrity constraints are identified during design and these constraints can be enforced by the DBMS.
4) Data sharing: The data stored in the database can be shared among multiple users or application programs. Same stored data can be used to create new applications.
5) Ease of application development: The application programs are easier to develop because DBMS handles issues like concurrent access,security and data integrity.
6) Data security: Since the data is stored centrally, enforcing security constraints is easy. Only authorised channels can access databases securely thanks to the DBMS.
7) Backup and recovery: The DBMS provides backup and recovery for hardware and software failures. 




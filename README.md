# Assignment: Bills Management System
As part of your learning journey into databases and data models, you will collaboratively design and implement a database for a Bills Management System. This system will help users track and manage their bills, including due dates, payment history, and bill categories. The assignment focuses on conceptualizing, designing, and applying relational data modeling principles.

<br/>

## Learning Objectives:
- Create an Entity-Relationship Diagram for a database.
- Define database schemas using SQL.
- Populate tables with sample data using SQL INSERT statements.
- Write SQL queries to retrieve and analyze data effectively.
- Demonstrate the working database with practical queries.


<br/>

### What you'll need:
- Access to a computer with internet access
- A code editor (e.g., Visual Studio Code)
- Familiarity with SQL commands, data modeling, and relational database principles..

### Scenario:
You are tasked with creating a Bills Management System database. You will design its structure, populate it with sample data, and write queries to interact with the system. Your output will showcase your understanding of database concepts and SQL.

<br/>

## Submission:
- Clone the project on your local computer
- Create a file named ```answers.sql```
- Run the queries on MySQL workbench and once they are successfull copy and paste on the ```answers.sql``` file on VS code
- Make sure you clearly comment your answers. Example:
```sql
-- question 1.1
SELECT * FROM table_one;

-- question 1.2
SELECT * FROM table_two;
```
- Once you finish the assignment, push the code to github

<br/>

## Part 1: Creating an Entity-Relationship Diagram
**1.1).** Design an ER diagram for a Bills Management System. Include key entities: <br/><br/>
  - Users (Attributes: UserID, Name, Email, Phone).
  - Bills (Attributes: BillID, UserID, Amount, DueDate, Category, Status).
  - Payments (Attributes: PaymentID, BillID, PaymentDate, PaymentAmount). <br/>

Clearly label primary and foreign keys and relationships between entities.


<br/>

## Part 2: Defining the Database Schema
**2.1).** Write SQL statements to define the database schema, including:  <br/>
  - Users table.
  - Bills table with foreign key reference to Users.
  - Payments table with foreign key reference to Bills.

<br/>

## Part 3: Comparison Operators
**3.1).** Populate the Users table with at least five records. Include:  <br/>
   - UserID, Name, Email, and Phone.

     <br/>
**3.2).** Populate the Bills table with at least ten records. Include:  <br/>
   - BillID, UserID, Amount, DueDate, Category (e.g., Utilities, Subscriptions), and Status (e.g., Paid, Unpaid).
     
      <br/> 
**3.3).** Populate the Payments table with at least five records. Include:  <br/>
   - PaymentID, BillID, PaymentDate, and PaymentAmount. Ensure valid BillID references.
     
      <br/> 

## Part 4: Writing SQL Queries
**4.1).**  Retrieve all unpaid bills from the Bills table. Display columns: <br/>
   - BillID, Amount, DueDate, and Status.
      <br/>
      
**4.2).** Group bills by category in the Bills table and calculate the total amount for each category. Display: <br/>
  -  Category, TotalAmount.
      <br/> 
      
**4.3).** Calculate the total unpaid amount due for the current month. Display: <br/>
  -  TotalDue.
      <br/> 
      
**4.4).** Retrieve the payment history for a user with UserID = 1. Display: <br/>
 -  PaymentID, BillID, PaymentDate, and PaymentAmount.
      <br/>

      
## Part 5: Demonstrating the Database
**5.1).** Create a demo of your database in MySQL Workbench or SQLite.
<br/>


<br/>

## Bonus Challenge (optional)
Write an SQL query to count the number of unpaid bills for each category.
Display the following columns: <br/>
 - Category
 - UnpaidBillsCount (number of unpaid bills per category)

<br/><br/>
## NOTE: Do not fork this repository

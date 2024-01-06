# Library-Management-Database-System

Our database for a library management system is designed to organize and process libraries and books. Our database comprises two main entities, books and publishers. It starts with the publisher, each one having a unique phone number, name, and address. Each book has a unique ID, title, author, and publisher. There are also other entities including library branches, book copies, book loans, and borrowers. The database finally supports various relationships, ensuring that operations will be effective and readers will have smooth transactions when checking books out.

![image](https://github.com/bhattaraimuna/Library-Management-Database-System/assets/112001777/62f2e15d-3e13-451e-950f-4f2a4494ccd7)

●	Book: The BOOK entity represents one book that will soon be stored in a library. Each book has a primary key which is the ID number and other attributes that are associated with the book are title, author, and publisher name. Books are then created to become book copies across different library branches, and then borrowers can borrow one or more books. 
●	Publisher: The PUBLISHER entity represents one or more people involved with publishing books that can be one or more books. Each publisher has a primary key which is the phone number and other attributes that also include their name and address. 
●	Library branch: The LIBRARY_BRANCH entity represents a physical location where book copies are stored and where borrowers can check them out using book loans. Each library branch has a primary key which is the branch ID and other attributes that have a name and address. 
●	Book copies: The BOOK_COPY entity represents physical copies of books available at one or more library branches. Each copy has a primary key of ID number and the number of copies. It is associated with a particular book and can allow tracking of how many books are left to be sent to one or more library branches.
●	Book loans: The BOOK_LOANS entity keeps track of the borrowing history of one or more books. Each book loan has a primary key of a card number and also has unique attributes such as book ID and branch ID. There are also other attributes such as return date and checked-out date. It creates a relationship between borrowers and library branches.
●	Borrower: The BORROWER entity consists of individuals who have library cards and can borrow books. Each borrower has a primary key of a card number and also has a unique attribute of phone number. The borrower also includes attributes such as name and address. 


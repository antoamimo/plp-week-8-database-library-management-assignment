My library management includes:

#Entities in the Library Management System
Members – people who borrow books.
Books – available books in the library.
Authors – each book has one or more authors.
Borrowings – records of members borrowing books.

#Relationships
One-to-Many: A member can borrow many books → Members → Borrowings.
Many-to-Many: A book can have multiple authors, and an author can write multiple books → handled with a junction table BookAuthors.
One-to-Many: A book can be borrowed many times → Books → Borrowings.

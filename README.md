1. Introduction
   
  The purpose of this project is to implement a Library Management System (LMS) using C++.
  The system manages a collection of books within a library. Each book has a unique identifier (ID), a title, and an author.
  The system allows adding books to the library, searching for a book by its unique ID, and printing all the books in the library.

The project involves working with the following core concepts:

  Classes: To represent the Book and Library entities.
  
  Linked Lists: To store and manage the books in the library.
  
  Basic Operations: Adding books, searching for books, and displaying all books.

2. Objectives
   
  To create a Book class that holds the book details: title, author, and id.
  
  To implement a Library class that stores the books using a linked list.
  
  To allow adding new books to the library.

  To search for a book by its unique id. 
  
  To display the details of all books in the library.

3. System Design
   
3.1 Classes and Data Structures

Book Class:

This class represents a single book and contains the following attributes:

  title: A string that stores the title of the book.
  
  author: A string that stores the author of the book.
  
  id: An integer that stores the unique ID for the book.

Node Class: 

A helper class used to implement the linked list. Each node contains:

  A pointer to a Book object (Book* book).
  A pointer to the next node (Node* next).

Library Class:

This class manages the collection of books using a linked list. It contains the following methods:

  addBook: Adds a new book to the library (linked list).
  
  searchById: Searches for a book by its unique ID.
  
  printAllBooks: Displays the details of all the books in the library.

3.2 Flowchart

The basic flow of the system can be visualized in the following steps:

  The system starts by creating a Library object.
  
  Books are added to the library via the addBook() function, which adds books to the beginning of the linked list.
  
  The user can search for a book using its unique ID through the searchById() function.
  
  All books can be listed using the printAllBooks() function.

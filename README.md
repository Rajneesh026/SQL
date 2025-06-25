# 📚 Library Management System Schema

This project includes the database schema for a Library Management System created as part of SQL Developer Internship Task 1.

## 🔧 Tables

- **Authors**: Stores information about book authors.
- **Books**: Stores all books available in the library.
- **Students**: Contains student details.
- **IssuedBooks**: Tracks which student issued which book and when.

## 🔗 Relationships

- One author can write many books.
- One student can issue many books.
- One book can be issued multiple times.

## 🧠 Concepts Used

- DDL (CREATE TABLE, PRIMARY KEY, FOREIGN KEY)
- Normalization (No redundancy)
- ER Diagram

## 📁 Files Included

- `schema.sql`: SQL script to create schema
- `ER_Diagram.png`: Entity-Relationship Diagram

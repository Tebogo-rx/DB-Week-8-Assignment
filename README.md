# DB-Week-8-Assignment7

# Project Description
This project is a Library Management System
- Tracks books, authors, and categories.
- Allow members to borrow, reserve, and return books
- Records and manage overdue fines.
- Enables staff to monitor member activity and bok availability.

Functinality:
- Book management(multiple authors, categories, copies).
- Member registration and status tracking.
- Bookvlending and reservation
- Fine imposition and payment tracking

# Table Roles
category - Stores book genres or classifications.
book - Core table for books with a link to category and number of copies.
author - Stores author info (first and last name).
book_author - Links books to one or more authors (many-to-many).
member - Tracks registered library members.
member_status - Indicates status (e.g. active, inactive, banned) of a member.
loan - Records when a book is borrowed and returned.
fine - Tracks late return fines per loan per member.
fine_payment - Logs payments made by members toward fines.
reservation - When all copies are borrowed, members can reserve books.
reservation_status - Status of a reservation (e.g. pending, fulfilled, canceled).

# ScreenShot
![Screenshot 2025-05-13 212908](https://github.com/user-attachments/assets/c766b57b-0111-4ed0-82c3-f32a780e5f85)

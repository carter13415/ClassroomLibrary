# Classroom Library System - Specification

## Project Overview
- **Project Name**: Classroom Library System
- **Type**: Responsive Web Application
- **Core Functionality**: Library management with book scanning, student tracking, and borrowing history
- **Target Users**: Teachers and students in a classroom setting

## Features

### Authentication
- **Teacher Login**: admin / admin
- **Student Login**: Individual credentials assigned by teacher
- **Teacher Signup**: Requires secret code (`orion_is_the_best`)

### Dashboard
- Stats: Total Books, Students, Borrowed, Overdue
- Quick actions: Add Book, Add Student, Sample Data, Export

### Book Management
- **Search Internet**: Type title or ISBN to search Open Library database
- Auto-fills title, author from search results
- Add books manually without search
- Optional custom Book ID (auto-generates if empty)
- Edit/delete books
- Search/filter books

### Student Management
- Add/edit/delete students
- Assign login credentials (username/password)
- View student login credentials (teachers only)
- View borrowed books per student

### Borrowing
- Browse all books
- Select book, choose student, checkout/return
- 14-day due date (auto-calculated)
- Overdue tracking

### Data Management
- LocalStorage persistence
- Export to JSON
- Load sample data

## Tech Stack
- HTML5, CSS3, Vanilla JavaScript
- LocalStorage for data persistence
- Open Library API for book search

## Book Search
Uses Open Library API (free, no key needed):
- Search by title, author, or ISBN
- Auto-fill book details
- Shows first sentence as description
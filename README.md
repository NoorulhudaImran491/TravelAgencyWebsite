# Travel Agency Website

## Table of Contents
- [Introduction](#introduction)
- [Project Objectives](#project-objectives)
- [Website Structure](#website-structure)
- [Technologies Used](#technologies-used)
- [Methodology](#methodology)
- [Database Schema](#database-schema)
- [Conclusion](#conclusion)

---

## Introduction
This project is a fully functional travel agency website that allows users to explore travel packages, read client reviews, and book travel services. The website uses HTML, CSS, and JavaScript for the front end, PHP for server-side scripting, and MySQL for the database.

## Project Objectives
- Create a user-friendly travel agency website.
- Provide detailed information about various travel packages.
- Implement a database to manage booking data effectively.

## Website Structure
- **Home Page**: Introduction to the travel agency.
- **About Page**: Client reviews and testimonials.
- **Packages Page**: List of travel packages with descriptions and prices.
- **Book Page**: Allows users to book a package and store details in the database.

## Technologies Used
- **HTML**: For structuring web pages.
- **CSS**: For styling and enhancing visual appeal.
- **JavaScript**: For client-side scripting and interactivity.
- **PHP**: For server-side scripting and handling database connections.
- **MySQL**: For database management.

## Methodology
1. **Front-End Development**: Implemented with HTML, CSS, and JavaScript.
2. **Back-End Development**: Server-side logic with PHP.
3. **Database Design**: Created a database named `book_db` to store booking information.

## Database Schema
The `book_form` table is used to store booking information:
```sql
CREATE TABLE `book_form` (
  `id` int NOT NULL AUTO_INCREMENT,
  `name` varchar(255) NOT NULL,
  `email` varchar(255) NOT NULL,
  `phone` varchar(15) NOT NULL,
  `address` varchar(255) NOT NULL,
  `location` varchar(255) NOT NULL,
  `guests` int NOT NULL,
  `arrivals` date NOT NULL,
  `leaving` date NOT NULL,
  PRIMARY KEY (`id`)
);

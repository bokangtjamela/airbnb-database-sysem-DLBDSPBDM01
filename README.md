# airbnb-database-sysem-DLBDSPBDM01
A full relational database system for an Airbnb-Style booking platform, including ERD design, SQL schema, sample datasets, documentation, and implementation phase.
![Logo](https://github.com/user-attachments/assets/5827d312-46e3-4f65-be68-2fd4bdeec344)


# Airbnb Database System
A complete relational database project designed for an Airbnb-style accomodation and experience booking platform. This repository includes the conceptual, logical and implementation phases of the database build, supported by SQL scripts, ERD diagrams, test data and documentation.

# Project Overview
This project implements a full database solution for a short-term rental platform similar to Airbnb. It covers the entire database development cycle:
* Conception Phase: requirements, entities, use-cases.
* Design Phase: conceptual ERD, logical ERD and relationships.
* Implementation Phase: SQL schema, constraints, test data, full database export.
* Documentation: visual ERD, table summaries and explanation notes

  - The system is built to manage users, hosts, guests, listings, bookings, payments, ametities, reviews, messages, notifications, reports, complaints and more.
 
# Features
- Complete SQL database schema
* Includes 23 normalized tables with: primary keys, foreign keys, refential integrity, data types, constraints.
* Realistic Sample Data - the repository includes a populated dataset with real-world scenarios for: users, hosts & guests, listings, bookings & payments, reviews, messages, notifications, reports & complaints, experiences.
* ERD diagrams: full conceptual ERD, final logical ERD (colourful, professional and fully connected).
* Documentation: visual table explanations, SQL examples, implementation notes and database export.

# Tech Stack
* MySQL - main database engine
* SQL - DDL + DML scripts
* ERD diagrams
* GitHub - version control & respository hosting

# Repository Structure
airbnb-database-system/
│
├── /erd/
│   ├── conceptual_erd.png
│   ├── full_logical_erd_coloured.png
│   └── erd.pdf
│
├── /sql/
│   ├── create_tables.sql
│   ├── insert_test_data.sql
│   ├── full_database_export.sql
│
├── /docs/
│   ├── table_descriptions.pdf
│   ├── implementation_summary.pdf
│   └── project_report.md
│
├── README.md
└── LICENSE (optional)

# How to Use This Project
* Clone the repository
- git clone
- https://github.com/bokangtjamela
* Import the Database
- Open MySQL Workbench
- Create new schema
- Import the full_database_export.sql file
* Run Test Queries
SELECT * FROM Listing;
SELECT * FROM Booking WHERE Status = 'Confirmed';
SELECT User.Name, Host.HostRating
FROM User
JOIN Host ON User.UserID = Host.UserID;

# ERD Diagram
![ERM_2](https://github.com/user-attachments/assets/3a74c6f6-e563-41b0-8836-82595047bc7b)

# Contributing
- Contributions are welcome!
- Feel free to open issues or submit pull requests.

# License
- ( Optional) MIT License - free to reuse and modify.

# Author
* Bokang Tjamela
* Contact: bokangkay7@gmail.com
* Creator and Designer of the Database System.


  

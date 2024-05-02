# Local-Eats-Guide

The objective of the study was to build a robust database management system for an online restaurant/eatery suggesting application called Local Eats Guide. The system is to handle both transactional data (payment information) Vendors data and Reference Data (User data, Address Information, Reviews etc), and should be the single source of information about anything related to users, vendors, events and the event organizers. First a conceptual data model was created which was later translated into an entity relationship model including cardinalities and relationships which was normalized to 3NF third normal form. Stored procedures, Views, User defined functons and 
<hr>

## Features

* **User Management:** Handles user information and preferences, including favorite dishes and cuisines.
* **Vendor Profiles:** Each vendor is detailed with information on cuisine, location, contact details, and operating hours.
* **Reviews and Ratings:** Users can post reviews and rate vendors, influencing future recommendations.
* **Event Management:** Vendors and event organizers can manage and promote events through the system.
* **Health Inspections:** Records and tracks health inspection results for vendors.
* **Payment Processing:** Manages event registration payments, ensuring secure transaction processing.
<hr>

## Entity-Relationship Diagram (ERD)

![image](https://github.com/Harsh-812/Local-Eats-Database/assets/135538639/7163e6ab-a676-4a27-97eb-9425e80cb763)
<hr>

## Advanced Database Features

* **Stored Procedures:** Includes procedures for fetching user details, adding new reviews, and calculating the average rating of a vendor.
* **Views:** Utilized for reporting purposes; views include user ratings/reviews, vendor cuisine details, and event registrations.
* **DML Triggers:** Automatically log new reviews and update user activity upon certain data changes.
* **CHECK Constraints:** Ensure data integrity by enforcing rules directly at the table level, such as valid rating ranges.
* **User-Defined Functions (UDFs):** Includes functions like calculating the total amount on the payment table.
* **Data Encryption:** Secures sensitive user data directly within the database.
* **Non-clustered Indexes:** Optimizes search performance without altering the physical order of the rows.
<hr>

## Database Design

The database is designed with the following key entities:

* **User:** Stores user details and their preferences.
* **Vendor:** Details about restaurant vendors including their offerings and operational details.
* **Events:** Information on events organized by vendors.
* **Health Inspection:** Logs inspection details for vendors to ensure compliance and safety.
* **Payment:** Manages payment transactions for event registrations

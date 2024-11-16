<h2 align="left">Executive Summary</h2>

<p align="justify">The Pharmacy Management System is a Full Stack platform designed to streamline the process of managing and ordering pharmaceutical products. It allows customers to browse available products, select items, and view the total cost in real time. Users can sign up, log in, and place orders, with options for online or manual payment. The system provides a user-friendly interface for both customers and pharmacy employees, reducing the manual effort of traditional store visits. Orders are processed efficiently by the pharmacy, ensuring minimal delay and quick order fulfilment. This system aims to enhance convenience for customers and improve operational efficiency for pharmacies.</p>

<h2 align = "left">Objective</h2>

<p align="justify">To build a Full Stack system that helps pharmacies effectively manage their inventory, orders, and streamline overall processes.</p>

<h2 align="left">Tech Stack</h2>

- Front End - HTML, CSS, SASS, JavaScript, Bootstrap  
- Database - SQL  
- Backend - Apache XAMPP, MySQL  
- Development Environment - VS Code, XAMPP Server  
- Version Control and Collaboration - GitHub  

<h2 align="left">Process Workflow</h2>

- Designed schema for the relational database structure.  
- Configured Apache XAMPP and MySQL database for development.  
- Developed front end for the purpose of user and store interaction.  
- The stored procedure implemented in the project is for displaying the deleted orders of users, which shows all the information about the order, such as the order date, number of items added to the order, the items added to the order, etc.  
- The trigger is implemented for inserting all details in the order table into a backup table (`order_ele`), which helps in maintaining a backup of all the deleted orders by users.  
- Established full-stack connection between the front end and back end.

<h2 align="left">Business Value</h2>

- Full-stack pharmacy management system to streamline pharmacy operations.  
- Database designed for efficient data storage and retrieval processes, following 3NF and ACID compliance.  
- Safely designed the application to ensure user data is encrypted and secure, with stored procedures and triggers implemented in the operations table.


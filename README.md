DBMS Interactive Visualizers
This repository contains a collection of interactive web-based visualizers designed to help students and enthusiasts understand fundamental concepts in Database Management Systems (DBMS).
Each visualizer focuses on a specific core topic, providing a hands-on approach to learning.

Table of Contents
DBMS Interactive Visualizers
Table of Contents
Features

Visualizers Included
1. DBMS Fundamentals Visualizer
2. ER/EER Diagram Builder
3. Relational Algebra Visualizer
4. Transaction Management Simulator

   
How to Use

1. Technologies Used
2. Contributing
3. License
4. Features


Interactive Learning: Engage with core DBMS concepts through direct manipulation and visualization.
Clear Explanations: Each visualizer includes concise descriptions and examples.
Dynamic Results: See the immediate impact of your actions and operations.
User-Friendly Interface: Simple and intuitive designs for easy navigation.

Visualizers Included

1. DBMS Fundamentals Visualizer
File: DBMS_Fundamentals_Visualizer.html

This visualizer provides an interactive overview of foundational DBMS concepts.

Three-Schema Architecture: Explore the External, Conceptual, and Internal schema levels and their role in data independence. Click on each layer to reveal detailed explanations and examples.
Schema vs. Instance: Understand the difference between the static blueprint (schema) and the dynamic data (instance) of a database. Toggle between schema and instance views for a sample table.
Advantages of DBMS over File Systems: Discover the key benefits of using a DBMS, such as reduced data redundancy, data independence, concurrent access, security, and robust backup/recovery mechanisms. 
Click on cards to expand comparisons.

2. ER/EER Diagram Builder
File: EER_Diagram_Builder.html

A tool to construct and visualize Entity-Relationship (ER) and Extended Entity-Relationship (EER) diagrams, and automatically generate a corresponding relational schema.

Drag-and-Drop Entities: Create entities on a canvas and position them freely.
Attribute Management: Add various types of attributes (simple, composite, derived, multivalued) to entities, and designate primary keys.
Relationship Creation: Define relationships between entities, specifying cardinality (1:1, 1:N, M:N).
Context Menus: Right-click on entities and attributes for quick actions like rename, delete, or set primary key.
Relational Schema Generation: Automatically convert your ER/EER diagram into a relational schema, displaying tables, columns, primary keys, and foreign keys.
This includes handling multivalued attributes and M:N relationships.
Clear Canvas: Reset the workspace to start a new diagram.

3. Relational Algebra Visualizer
File: Relational_Algebra_Visualizer.html

An interactive tool to perform fundamental relational algebra operations on in-memory tables.

Create Custom Relations: Define your own tables with specified names and columns, and populate them with data.
Supported Operations:
SELECT : Filter rows based on a given condition.
PROJECT: Select specific columns from a relation.
JOIN : Combine rows from two relations based on a join condition.
UNION : Combine rows from two union-compatible relations.
DIFFERENCE : Find rows present in one relation but not in another (union-compatible).
Dynamic Results: See the output of each operation immediately in a new result table.
Sample Data: Pre-loaded sample tables (Students, Courses, Enrollments) to get started quickly.

4. Transaction Management Simulator
File: Transaction_Management_Simulator.html

This simulator helps in understanding transaction states, ACID properties, and concurrency control issues like dirty reads, along with privilege management.

Transaction States: Step through the lifecycle of a transaction (Active, Partially Committed, Committed, Failed, Aborted) with descriptions for each state.
ACID Properties: Explore Atomicity, Consistency, Isolation, and Durability through interactive demonstrations and explanations.
Dirty Read Scenario: Visualize a dirty read anomaly between two concurrent transactions (T1 and T2) and understand its implications.
GRANT and REVOKE Privileges: Simulate granting and revoking database privileges (SELECT, INSERT, UPDATE, DELETE, ALL) to different user roles (Admin, Manager, Analyst, Guest) and observe the changes in their access rights.

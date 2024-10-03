# Oracle PDB Management for PLSQL Class

# This repository contains the instructions and SQL scripts related to the creation, management, and deletion of Oracle Pluggable Databases (PDBs) for the PLSQL Class 2024. The tasks outlined will be used throughout the course for various exercises and projects.

# Project Tasks

# Task 1: Create a Pluggable Database (PDB)
The first task involves creating a new Pluggable Database (PDB), which will be used for class activities. This PDB will store all the work and exercises during the course. A unique username and password are required for accessing this PDB.

# Steps to Create the PDB:

# Connect to the Container Database (CDB) as a privileged user (e.g., sysdba).
Create the PDB using the SQL command that specifies the new PDB's name and assigns an admin user.

# Open the PDB to make it accessible for use in class activities.
Verify the PDB creation using SQL commands to check its status.
Task 2: Create and Delete a Temporary Pluggable Database
In this task, you will create a second PDB for practice purposes, which will be deleted afterward. This temporary PDB is created, opened, and verified just like the first, but is then dropped (deleted) once confirmed.

# Steps to Create and Delete the PDB:

# Create the Temporary PDB following the same procedure used for the first PDB.
Open the PDB to ensure it is functional.

# Close and Drop the PDB using SQL commands, making sure to remove the data files as well.
# Repository Contents

# SQL scripts for creating, managing, and deleting Pluggable Databases.
Sample commands to verify the creation and deletion of PDBs.
Instructions on how to connect to the Oracle database and manage the state of PDBs.
Prerequisites

# Oracle Database with Container and Pluggable Database functionality enabled.
Necessary privileges to create, open, and delete PDBs.
Basic understanding of SQL and Oracle Database administration.
This repository provides all necessary resources and instructions to manage Oracle PDBs as part of the class. You can explore the SQL scripts and adapt them for your own Oracle environment.

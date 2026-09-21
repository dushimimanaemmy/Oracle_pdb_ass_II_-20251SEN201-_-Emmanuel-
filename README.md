#  Oracle Pluggable Databases Management
## NAME: DUSHIMIMANA Emmanuel
## ID: 20251SEN201
## Overview my assignment.
### This assignment demonstrates practical understanding of Oracle Multitenant Pluggable Database management, User creation and management inside a PDB, Oracle Enterprise Manager (OEM), and professional technical documentation using GitHub.

## The assignment contain fur mandatory tasks:
### 1.Create a New pluggable Database
### 2.Create and Delete a PDB
### 3.COnfigure and Access Oracle Enterprise Manager(OEM)
### 4.Document the work professionally on GitHub

### The assignment was completed using the following environment
### Database: Oracle Database
### Tool: SQLPLUS and Oracle SQL Developer
### Management Toll: Oracle Enterprise Manager(OEM)
### Documentation platform : GitHub

### First event I opened sqlplus it connect and open SQL Developer all followed instruction to connect.
### before answers the Question I connect oracle database to SQl developer using username like sys as sysdba and password.

## Task1: I started for checking container database(CDB) and Create Pluggable Database.
### Query: help to display CDB.
SHOW CON_NAME;
### Query that used to create Pluggable Database is
CREATE PLUGGABLE DATABASE Em_pdb_20251SEN201 ADMIN USER Emmanuel_plsqlauca_20251SEN201 IDENTIFIES BY pass54325;
## OUTPUT FROM RUNNING QUERY IN TASK ONE


### After create pdb from Exist pluggable database to new created pluggable database pdb I opened using this query:-
ALTER SESSION SET CONTAINER=Em-20251SEN201;
### then show container pdb name

### I was run a query that helped to open PDBS and show pdb.
### output show how can open pdb after created and show it all it contain this image and their image


### Task2: I Created temporary PDB using  below query
CREATE PLUGGABLE DATABASE Em_to_delete_pdb_20251SEN201 ADMIN USER Emmanuel_plsqlauca_20251SEN201 BY IDENTIFIES Temp54325;
### After to create PDB you need to make command haht help to open using this query such as..
ALTER PLUGGABLE DATABSE Em-to-delete_pdb_20251SEN201 open;
### Then use command to like after press Enter: show PDBs
### Output show all above task two and contain their image


### Task3: I tried to access Oracle Enterprise Manager (OEM) but not happen because OEM not agree my credentials container name not allow. 
### OUTPUTS SHOW RESULTS open this link: 
https://github.com/dushimimanaemmy/Oracle_pdb_ass_II_-20251SEN201-_-Emmanuel-/blob/76f675beebf964f73ef93d246d7911b2a5c4956a/Screenshots/TAsk3_OEM.png


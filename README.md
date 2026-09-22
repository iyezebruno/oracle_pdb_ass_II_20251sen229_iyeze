# Oracle PDB Management Assignment II


Student Name: Iyeze  
Student ID: 20251SEN229  
Course: Database Development with PL/SQL  

## Project Purpose

The purpose of this practical assignment was to practice Oracle Multitenant Database management.

The work included creating a Pluggable Database, opening it for use, checking a user inside the PDB, creating and removing a temporary PDB, and viewing the Oracle environment using Enterprise Manager.

## System Used

The practical work was completed using:

- Oracle Database 21c Enterprise Edition
- Oracle SQL Developer
- Oracle Enterprise Manager Database Express
- Windows 64-bit
- Database SID: ORCL

## Task 1: Main Pluggable Database

The main PDB created for this assignment was:

`IY_PDB_20251SEN229`

The following steps were completed:

1. I checked that I was connected to `CDB$ROOT`.

2. I created the new Pluggable Database named:

   `IY_PDB_20251SEN229`

3. I checked the available PDBs and confirmed that the new PDB was created.

4. After creation, the PDB first appeared with the status:

   `MOUNTED`

5. I opened the PDB so that it could be used normally.

6. I checked the PDB status again and confirmed that it changed to:

   `READ WRITE`

7. I changed the current container to:

   `IY_PDB_20251SEN229`

8. I verified that the required user existed inside the PDB.

   The username was:

   `IYEZE_PLSQLAUCA_20251SEN229`

9. I confirmed that the username was displayed successfully.



## Task 2: Create and Delete a Temporary PDB

The temporary PDB used in this task was:

`IY_TO_DELETE_PDB_20251SEN229`

The following steps were completed:

1. I made sure that I was connected to `CDB$ROOT`.

2. I created the temporary Pluggable Database named:

   `IY_TO_DELETE_PDB_20251SEN229`

3. I checked the available PDBs to confirm that it was created.

4. The temporary PDB appeared with the status:

   `MOUNTED`

5. I deleted the temporary PDB together with its data files.

6. I checked the available PDBs again.

7. I confirmed that:

   `IY_TO_DELETE_PDB_20251SEN229`

   was no longer shown in the PDB list.



## Task 3: Oracle Enterprise Manager

Oracle Enterprise Manager Database Express was used to check the Oracle database environment.

The following steps were completed:

1. I opened Oracle Enterprise Manager Database Express in a web browser.

2. I logged in to the Oracle database.

3. I opened the Database Home dashboard.

4. I confirmed that the dashboard showed Oracle Database 21c.

5. I checked the database information and confirmed that the database was running as a CDB with two PDBs.

6. I checked the database performance and storage information.

7. I confirmed that the PDB created during Task 1 was shown in the Oracle environment.

8. I confirmed that the logged-in username `SYS` was visible on the dashboard.

9. I captured a screenshot of the Oracle Enterprise Manager dashboard as evidence.


## Evidence

Screenshots were taken during the practical work to show:

### PDB Creation
- Main PDB creation
- PDB status before opening
- PDB status after opening
- User verification

### PDB Deletion
- Temporary PDB creation
- Temporary PDB verification
- Temporary PDB deletion
- Confirmation that the PDB was removed

### Oracle Enterprise Manager
- Database Home dashboard
- Oracle environment information
- PDB information
- Logged-in username

## Challenges and Learning

One important thing learned during the assignment was the difference between the `MOUNTED` and `READ WRITE` states.

After creating a PDB, it was first shown as `MOUNTED`. The PDB had to be opened before it could be used normally.

The assignment also helped improve understanding of Oracle PDB creation, database users, PDB deletion, and Oracle Enterprise Manager.

## Integrity Statement

I performed the practical database activities in my Oracle environment and captured the screenshots during the work. The screenshots included in this repository show the results of the tasks that were completed.

## Submission Details

Repository Link: https://github.com/iyezebruno/oracle_pdb_ass_II_20251sen229_iyeze.git

PDB Name Created: IY_PDB_20251SEN229

Issues Encountered: No major issues

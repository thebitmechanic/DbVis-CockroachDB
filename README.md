DbVis-CockroachDB
=======================

DbVis Database Profile for CockroachDB

Features
============

- Database listing
  - Each database lists it's virtual schemas and their underlying system views
- Sequence listing
  - View information about the sequence and see its source
- Sequence actions
  - Create, alter, drop, and rename
- Table listing
  - View columns, indexes, data, and source
- Table actions
  - Drop and rename columns
- View listing
  - View data and source
- View actions
  - Drop and rename

Requirements
============

* DbVisualizer Pro (the free version does not support custom profiles) 
* CockroachDB 2.1

Installation
============
- Place the profile in any directory.
- Add the directory as a search path for Database Profile Paths in Preferences.
- Restart DbVisualizer.
- Create a connection using the PostgreSQL JDBC driver.
- In the Properties tab for the connection, manually choose the database profile cockroachdb.
- Connect to the database.

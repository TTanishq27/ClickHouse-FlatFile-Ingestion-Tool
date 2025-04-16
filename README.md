1. Built a web application with a simple user interface using HTML/CSS/JavaScript and a Flask backend.

2. Enabled bidirectional data flow:
    . From ClickHouse to Flat File (CSV)
    . From Flat File to ClickHouse

3. Implemented JWT token-based authentication for secure ClickHouse connections.

4. UI allows:
    . Selecting the data source (ClickHouse or Flat File)
    . Entering connection details for ClickHouse and file info for CSV
    . Listing ClickHouse tables and their columns
    . Selecting specific columns for ingestion using checkboxes
   
6. Added action buttons: Connect, Load Columns, Preview, Ingest

7. Built status indicators to show progress (Connecting, Ingesting, Completed, Error)

8. Shows record count after successful ingestion

9. Added data preview feature to display first 100 rows before ingestion

10. Supported multi-table JOIN with user-defined join conditions

11. Handled basic errors: connection issues, auth errors, query failures, and ingestion errors

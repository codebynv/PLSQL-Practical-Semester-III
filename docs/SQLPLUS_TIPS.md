# SQL*Plus Tips

## Output

Enable server output when a practical uses DBMS_OUTPUT:

    SET SERVEROUTPUT ON;

## Running a script

    @filename.sql

A PL/SQL block is commonly executed with:

    /

## Debugging

When a script behaves unexpectedly:

1. Check the exact input values.
2. Read the complete Oracle error.
3. Identify the statement that failed.
4. Test the smallest failing section.
5. Re-run after correcting the cause.

Keep database credentials and local connection configuration outside version control.

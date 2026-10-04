# PL/SQL Debugging Guide

When a practical fails:

1. Read the complete Oracle error.
2. Check the input values.
3. Confirm table and column names.
4. Inspect cursor state when using cursors.
5. Isolate the failing statement.
6. Re-run after correcting the root cause.

For cursor programs, pay particular attention to OPEN, FETCH, loop termination, and CLOSE behavior.

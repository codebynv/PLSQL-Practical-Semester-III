# SELECT INTO Guide

SELECT INTO is used when a query is expected to assign values to PL/SQL variables.

## Important cases

- No matching row can raise NO_DATA_FOUND.
- Multiple matching rows can raise TOO_MANY_ROWS.
- Selected values should match the receiving variables.

When practicing, deliberately test both successful and exceptional cases to understand the behavior.

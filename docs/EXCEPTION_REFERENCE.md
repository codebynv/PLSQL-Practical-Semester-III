# Exception Reference

PL/SQL exceptions should communicate what went wrong and allow the program to recover or terminate predictably.

## Common categories

- Predefined Oracle exceptions
- User-defined exceptions
- `NO_DATA_FOUND`
- `TOO_MANY_ROWS`
- `ZERO_DIVIDE`

## Practice

When debugging an exception, identify the statement that raised it before changing the exception handler. Avoid swallowing errors without understanding their cause.

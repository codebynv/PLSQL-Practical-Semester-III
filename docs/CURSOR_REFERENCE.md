# Cursor Reference

## Explicit cursor lifecycle

    DECLARE
      cursor
      ↓
      OPEN
      ↓
      FETCH
      ↓
      PROCESS
      ↓
      CLOSE

## Important attributes

- %FOUND
- %NOTFOUND
- %ROWCOUNT
- %ISOPEN

For parameterised cursors, verify that the supplied parameters match the intended query conditions.

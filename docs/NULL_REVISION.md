# SQL NULL Revision

- NULL represents an unknown or missing value, not zero or an empty string.
- Use IS NULL and IS NOT NULL to test for NULL.
- Comparisons such as = NULL do not evaluate to TRUE.
- COUNT(column) ignores NULL values; COUNT(*) counts rows.
- Use COALESCE or the database-appropriate equivalent when a fallback is intended.

Try each example against a small table containing both NULL and non-NULL values.
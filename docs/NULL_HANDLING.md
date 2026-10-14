# SQL NULL Handling

NULL represents a missing or unknown value; it is not equal to zero or an empty string.

## Revision points

- Use IS NULL and IS NOT NULL to test nullness.
- Understand how NULL affects comparisons.
- Check aggregate behavior with NULL values.
- Consider NVL or COALESCE when a default is appropriate.
- Test expressions with both NULL and non-NULL input.

Do not replace NULL with a default unless that behavior matches the problem requirements.

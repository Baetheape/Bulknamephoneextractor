# Bulk Name → Phone Extractor

This actor takes a bulk list of names (one per line), searches CyberBackgroundChecks,
opens the first matching profile, and extracts up to 5 phone numbers.

## Input
Paste names into the textarea:

```
John Doe
Maria Hernandez
James Carter
```

## Output
Dataset rows containing:
- first_name
- last_name
- phone_1 … phone_5
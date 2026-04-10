# Medical Records Validator 🏥

A Python script that validates the structure and format of medical 
records using regex pattern matching and dictionary-based constraint checking.

Validates each record for correct field types, formats, and values —
reporting exactly which fields fail and at which position.

## What it does

- Checks that each record contains all required fields
- Validates field types and formats using regex
- Reports invalid fields with their position in the dataset
- Handles edge cases like missing keys and wrong data types

## Concepts
`re` module, regex pattern matching, dictionary unpacking, set operations,
input validation, generator expressions, enumerate

Built with: Python 3

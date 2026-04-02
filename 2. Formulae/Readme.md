# Google Sheets Formulas Roadmap

## Introduction
Formulas are the backbone of Google Sheets, enabling you to perform calculations, manipulate data, and automate tasks. This roadmap covers everything from basic to advanced formulas and functions.

## Table of Contents
1. [Basic Arithmetic Formulas](#basic-arithmetic-formulas)
2. [Common Functions](#common-functions)
3. [Logical Functions](#logical-functions)
4. [Lookup and Reference Functions](#lookup-and-reference-functions)
5. [Text Functions](#text-functions)
6. [Date and Time Functions](#date-and-time-functions)
7. [Array Formulas](#array-formulas)
8. [Financial Functions](#financial-functions)
9. [Statistical Functions](#statistical-functions)
10. [Error Handling](#error-handling)
11. [Advanced Formulas](#advanced-formulas)

## Basic Arithmetic Formulas

### Addition
- **Formula**: `=A1 + B1`
- **Description**: Adds the values in cells A1 and B1.

### Subtraction
- **Formula**: `=A1 - B1`
- **Description**: Subtracts the value in cell B1 from the value in cell A1.

### Multiplication
- **Formula**: `=A1 * B1`
- **Description**: Multiplies the values in cells A1 and B1.

### Division
- **Formula**: `=A1 / B1`
- **Description**: Divides the value in cell A1 by the value in cell B1.

### Exponentiation
- **Formula**: `=A1 ^ B1`
- **Description**: Raises the value in cell A1 to the power of the value in cell B1.

## Common Functions

### SUM
- **Formula**: `=SUM(A1:A10)`
- **Description**: Sums the values in the range A1 to A10.

### AVERAGE
- **Formula**: `=AVERAGE(A1:A10)`
- **Description**: Calculates the average of the values in the range A1 to A10.

### COUNT
- **Formula**: `=COUNT(A1:A10)`
- **Description**: Counts the number of numeric values in the range A1 to A10.

### COUNTA
- **Formula**: `=COUNTA(A1:A10)`
- **Description**: Counts the number of non-empty cells in the range A1 to A10.

### MIN
- **Formula**: `=MIN(A1:A10)`
- **Description**: Returns the smallest value in the range A1 to A10.

### MAX
- **Formula**: `=MAX(A1:A10)`
- **Description**: Returns the largest value in the range A1 to A10.

## Logical Functions

### IF
- **Formula**: `=IF(A1 > 10, "Yes", "No")`
- **Description**: Returns "Yes" if the value in A1 is greater than 10, otherwise returns "No".

### AND
- **Formula**: `=AND(A1 > 10, B1 < 20)`
- **Description**: Returns TRUE if both conditions are true.

### OR
- **Formula**: `=OR(A1 > 10, B1 < 20)`
- **Description**: Returns TRUE if at least one condition is true.

### NOT
- **Formula**: `=NOT(A1 > 10)`
- **Description**: Returns TRUE if A1 is not greater than 10.

## Lookup and Reference Functions

### VLOOKUP
- **Formula**: `=VLOOKUP(search_key, range, index, [is_sorted])`
- **Description**: Searches for a key in the first column of a range and returns the value in the same row from a specified column.

### HLOOKUP
- **Formula**: `=HLOOKUP(search_key, range, index, [is_sorted])`
- **Description**: Searches for a key in the first row of a range and returns the value in the same column from a specified row.

### INDEX
- **Formula**: `=INDEX(range, row, [column])`
- **Description**: Returns the value of a cell in a specified row and column of a range.

### MATCH
- **Formula**: `=MATCH(search_key, range, [search_type])`
- **Description**: Returns the position of a specified value in a range.

## Text Functions

### CONCATENATE
- **Formula**: `=CONCATENATE(A1, " ", B1)`
- **Description**: Combines the values in cells A1 and B1 with a space in between.

### LEFT
- **Formula**: `=LEFT(A1, 5)`
- **Description**: Returns the first 5 characters from the left of the text in cell A1.

### RIGHT
- **Formula**: `=RIGHT(A1, 5)`
- **Description**: Returns the last 5 characters from the right of the text in cell A1.

### MID
- **Formula**: `=MID(A1, start, num_chars)`
- **Description**: Returns a segment of text from cell A1 starting at a specified position.

### LEN
- **Formula**: `=LEN(A1)`
- **Description**: Returns the length of the text in cell A1.

## Date and Time Functions

### TODAY
- **Formula**: `=TODAY()`
- **Description**: Returns the current date.

### NOW
- **Formula**: `=NOW()`
- **Description**: Returns the current date and time.

### DAY
- **Formula**: `=DAY(A1)`
- **Description**: Returns the day of the month from the date in cell A1.

### MONTH
- **Formula**: `=MONTH(A1)`
- **Description**: Returns the month from the date in cell A1.

### YEAR
- **Formula**: `=YEAR(A1)`
- **Description**: Returns the year from the date in cell A1.

## Array Formulas

### ARRAYFORMULA
- **Formula**: `=ARRAYFORMULA(A1:A10 * B1:B10)`
- **Description**: Performs an operation on entire columns or rows.

### TRANSPOSE
- **Formula**: `=TRANSPOSE(range)`
- **Description**: Transposes the rows and columns of a range.

## Financial Functions

### PV
- **Formula**: `=PV(rate, nper, pmt, [fv], [type])`
- **Description**: Calculates the present value of an investment.

### FV
- **Formula**: `=FV(rate, nper, pmt, [pv], [type])`
- **Description**: Calculates the future value of an investment.

### PMT
- **Formula**: `=PMT(rate, nper, pv, [fv], [type])`
- **Description**: Calculates the payment for a loan based on constant payments and a constant interest rate.

## Statistical Functions

### STDEV
- **Formula**: `=STDEV(A1:A10)`
- **Description**: Estimates the standard deviation based on a sample.

### MEDIAN
- **Formula**: `=MEDIAN(A1:A10)`
- **Description**: Returns the median value in a range.

### MODE
- **Formula**: `=MODE(A1:A10)`
- **Description**: Returns the most frequently occurring value in a range.

## Error Handling

### IFERROR
- **Formula**: `=IFERROR(value, value_if_error)`
- **Description**: Returns a specified value if a formula results in an error.

### ISERROR
- **Formula**: `=ISERROR(A1)`
- **Description**: Returns TRUE if the value in cell A1 is an error.


## Advanced Formulas

### QUERY
- **Formula**: `=QUERY(data, query, [headers])`
- **Description**: Runs a Google Visualization API Query Language query across data.

### IMPORTRANGE
- **Formula**: `=IMPORTRANGE(spreadsheet_url, range_string)`
- **Description**: Imports a range of cells from a specified spreadsheet.

### REGEXMATCH
- **Formula**: `=REGEXMATCH(text, regular_expression)`
- **Description**: Whether a piece of text matches a regular expression.

### REGEXEXTRACT
- **Formula**: `=REGEXEXTRACT(text, regular_expression)`
- **Description**: Extracts matching substrings according to a regular expression.

## Conclusion
This roadmap covers a wide range of formulas and functions in Google Sheets. Mastering these will enable you to perform complex calculations, data analysis, and automation tasks efficiently.
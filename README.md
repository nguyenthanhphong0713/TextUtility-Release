# TextUtility-Release
Release Repo for TextUtility

<img width="834" height="543" alt="image" src="https://github.com/user-attachments/assets/fa8f84d3-f5fd-4e86-8631-47270f4bb427" />

# String & SQL Utility Tool

A lightweight utility designed for converting strings between rows and columns, cleaning text data, and handling string formatting or SQL query manipulations based on predefined templates.

## Key Features

The tool provides 11 specialized modes divided into 3 main categories:

### 1. Row & Column Conversion

* **Split string to rows:** Split a single delimited string into multiple lines using a custom split character (e.g., `,`, `;`, `|`).
* **Join rows to string:** Merge multiple lines into a single string with custom delimiters and optional string wrapping (`Wrap string`).

### 2. Text Cleaning & Sorting

* **Remove Duplicate Lines:** Filter out and remove duplicate rows to keep only unique values.
* **Sort Lines A → Z:** Sort all rows in ascending alphabetical order.
* **Sort Lines Z → A:** Sort all rows in descending alphabetical order.
* **Remove Empty Lines:** Clean up text by stripping out all blank or whitespace-only lines.

### 3. SQL & Developer Utilities

* **SQL IN Clause (Smart):** Format a list of rows into a ready-to-use SQL `IN ('val1', 'val2', ...)` clause.
* **Clear Changed Database context:** Strip out `Changed database context to...` messages or `USE [Database]` statements from SQL scripts/logs.
* **Regex Extract Matches:** Extract specific text patterns from source strings using Regular Expressions (Regex).
* **SQL REPLACE / CASE Beautify:** Format and indent nested SQL `REPLACE` or complex `CASE WHEN` statements to make them readable.
* **SQL REPLACE / CASE Unbeautify:** Minify formatted SQL `REPLACE` or `CASE` statements back into a compact, single-line string.

## Quick Usage

1. **Select Mode:** Choose the transformation mode from the **Mode** dropdown menu.
2. **Configure Options:** Set the **Split character** or **Wrap string** template if applicable.
3. **Input Data:** Paste raw text or SQL snippets into the **Source** box.
4. **Get Result:** Copy the transformed output for use in your project or database query.

## Author

* **Nguyen Thanh Phong** - *Technical Project Manager | Enterprise ERP Systems | Software Developer*


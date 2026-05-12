# SQL Notes (In Progress as of 5/11/2026 2:41pm HST)

These are my personal SQL notes as I build stronger data analysis and data engineering skills. I am using this file to document core SQL concepts, practice query patterns, common mistakes I make, and lessons I learned from exercises and mini-projects.

My goal is to become stronger at writing clean, accurate SQL for data analyst, risk operations, trust and safety, fraud analysis, and junior data engineering work.

## 1. What SQL Is 
SQL stands for Structured Query language. It is used to query, analyze, and manage data stored in relational databases.

## SELECT

### What it does

`SELECT` chooses which columns I want to return from a table.

### When I use it

I use `SELECT` whenever I need to inspect data, pull specific fields, or start building an analysis query.

### Example

```sql
SELECT customer_id, order_date, total_amount
FROM orders;

## 2. Query Pattern Sections
You should organize your notes by **query pattern**, not just definitions.

# Recommended sections:
```markdown
## Basic Query Structure
## Filtering with WHERE
## Sorting with ORDER BY
## Limiting Results
## Aggregations
## GROUP BY
## HAVING
## Joins
## CASE Statements
## Subqueries
## Common Table Expressions
## Window Functions
## NULL Handling
## Date and Time Queries
## Data Cleaning Patterns
## Data Validation Checks
## Analyst Thinking Checklist
Before writing a query, I should ask:

1. What question am I trying to answer?
2. What table contains the data?
3. What is the unit of analysis?
4. Am I looking at users, orders, transactions, cases, or events?
5. What filters are required?
6. Are there NULL values?
7. Are there duplicates?
8. Do I need row-level data or summary-level data?
9. Could a join multiply rows?
10. How can I validate the result?

## Career Use Cases

### Data Analyst
SQL helps me pull, clean, summarize, and analyze data for business questions.

### Risk Operations Analyst
SQL can be used to review suspicious activity, case patterns, user behavior, payment issues, and operational trends.

### Trust and Safety Analyst
SQL can help identify abuse patterns, enforcement trends, policy violations, and user reports.

### Fraud Analyst
SQL can help investigate transaction anomalies, duplicate accounts, suspicious velocity patterns, and high-risk behavior.

### Junior Data Engineer
SQL is foundational for transforming data, validating pipelines, creating tables, and preparing datasets for reporting.

## Mini-Project Notes
## SQL Vocabulary
## Questions I Still Need to Understand

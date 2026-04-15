# web-security-labs

# SQL Injection - WHERE Clause Bypass

## Objective
Retrieve hidden data using SQL injection.

## Vulnerability
The category parameter is directly used in SQL query without sanitization.

## Payload used
' OR 1=1--

## What happened
The WHERE condition was bypassed and all products (including hidden ones) were displayed.

## Key learning
- OR 1=1 always evaluates to TRUE
- -- comments out the rest of SQL query
- Unsanitized input leads to SQL injection

## Result
Lab successfully solved.

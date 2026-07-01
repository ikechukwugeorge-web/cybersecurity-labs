# SQL Injection

## Overview

This exercise was completed in DVWA to understand how SQL Injection works and how attackers can manipulate database queries when user input is not properly validated.

## What the Screenshots Show

The screenshots show the SQL Injection payloads I tested against the application. By using UNION based SQL Injection, I was able to retrieve information from the database, including table names and user data. The screenshots also show the successful output returned by the application after the payloads were executed.

## What I Learned

This lab helped me understand how SQL Injection can expose sensitive information when applications build SQL queries using unsanitized user input.

I learned how UNION based SQL Injection can be used to retrieve data from other tables and how the information_schema database can reveal database structure, including available tables and columns. I also learned how attackers may obtain password hashes if applications are vulnerable.

Completing this exercise reinforced the importance of using parameterized queries, validating user input, limiting database permissions, and avoiding detailed database error messages.

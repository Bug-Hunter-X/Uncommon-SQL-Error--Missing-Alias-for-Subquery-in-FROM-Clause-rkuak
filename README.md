# Uncommon SQL Error: Missing Alias for Subquery in FROM Clause

This repository demonstrates a common SQL error involving a missing alias for a subquery in the FROM clause.  Many developers are familiar with subqueries in the WHERE clause, but using them in the FROM clause often requires extra attention to syntax.  The provided example will aid in understanding and avoiding this type of error.

## Problem
The `bug.sql` file contains a SQL query that attempts to count the number of orders for each customer. The subquery counts orders per customer, but it lacks an alias, leading to a syntax error. This is a less frequently encountered issue compared to other SQL errors.

## Solution
The `bugSolution.sql` file demonstrates the correct solution.  The key change is adding an alias to the subquery. This allows the main query to correctly reference the subquery's results.
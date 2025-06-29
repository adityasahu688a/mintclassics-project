# Mint Classics Portfolio Project

## Project Overview
Analyzes the Mint Classics database to optimize inventory and close a warehouse while maintaining 24-hour fulfillment.

## Techniques
- SQL queries in MySQL Workbench for inventory, sales, and what-if analysis.
- Data exploration using EER diagram and table data.
- Workaround for missing inventory table with capacity-adjusted distribution.

## Findings
- Overstocked: 9,753 units of S18_1342 (1999 Indy 500 Monte Carlo SS).
- Non-moving: 5 products, 4,500+ units unsold since June 29, 2024.
- Warehouse c (50% capacity) underutilized.

## Recommendations
- Close Warehouse c, reduce stock by 20%, discontinue non-moving items.
- Ensure service via office proximity (e.g., San Francisco for USA).

## Files
- `/sql_scripts`: Query scripts.
- `/results`: CSV exports.
- `/report`: Analysis report.
- `/visuals`: Supporting charts.

## Limitations
- Missing warehouse-specific stock and shipping data.

## Setup
- Import `mintclassicsDB.sql` into MySQL Workbench.
- Run queries and analyze results.

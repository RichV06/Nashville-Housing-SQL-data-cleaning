# Nashville Housing: Data Cleaning in SQL

Cleaning of the Nashville Housing dataset in SQL Server to make it ready for analysis.

## Steps (`Nashville Housing SQL.sql`)
- Standardize the sale date format
- Fill missing property addresses using a self-join on `ParcelID`
- Split address fields into separate columns (address, city, state)
- Normalize categorical values
- Remove duplicate records
- Drop unused columns

## SQL skills
Self-joins, `ISNULL`, `SUBSTRING`/`CHARINDEX`, `PARSENAME`, `CASE`, CTEs with `ROW_NUMBER()`, `ALTER`/`UPDATE`.

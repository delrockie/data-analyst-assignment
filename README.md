# Data Analyst Assignment

## Dataset Chosen
I chose the dataset on [Netflix Shows](#).

## Import Process
1. Created a new database in MySQL Workbench.
2. Imported the dataset using the Data Import feature.
3. Faced difficulty with encoding issues but resolved them by specifying the correct character set.

## Interesting Observation
One interesting thing I noticed was the diverse range of genres available in the Netflix Shows dataset.

## Data Fun
### Cool Fact 1
```sql
SELECT genre, COUNT(*) AS count FROM netflix_shows GROUP BY genre ORDER BY count DESC;

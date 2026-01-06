# Databases
- A data model is a collection of concepts for describing the data in a database.
- Rules that define the types of things that could exist and how they relate.
- (i.e. relation, document, …)
- A schema is a description of a particular collection of data, using a given data model.
- This defines the structure of database for a data model. Otherwise, you have random bits with no meaning.
- SQL is based on bags (duplicates), not sets (no duplicates).
- Aggregations can't be executed with other fields in a SELECT statement if no GROUP BY clause is defined.
- GROUPING SETS are better thatn multiple queries with aggregation with a UNION ALL for grouping the results.
- HAVING clause filters groups, runs after GROUP BY, and can contain aggregations.
  - WHERE -> Remove rows
  - HAVING -> Remove groups
---
# References
- [CMU Intro to Database Systems (15-445/645 - Fall 2025)](https://youtube.com/playlist?list=PLSE8ODhjZXjYMAgsGH-GtY5rJYZ6zjsd5&si=TTVsBz0ncg3ptPG3)

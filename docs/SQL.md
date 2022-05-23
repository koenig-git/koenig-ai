---
layout: page
title: SQL
description: >
  Lorem Ipsum dolor sit amet.
hide_description: true
sitemap: false
---
0. this unordered seed list will be replaced by toc as unordered list
{:toc}

## Querying Data
The general syntax is structured as:
```sql
SELECT select_list INTO new_table
FROM table_source 
[ WHERE search_condition ]
[ GROUP BY group_by_expression ]
[ HAVING search_condition ]
[ ORDER BY order_expression [ ASC | DESC ] ];
```
SQL leaves it to the database which statemets are executed first. To read select statements efficiently, start with the *FROM* statement. Lets break down each individual statement

### SELECT Columns
After SELECT we need to specify which data fields (columns) we want to query. We can opt for single, multiple or all columns as well as functions for aggregating data.

| Specifier |Functionality| 
|:-----------------|:-----------|
| \*        | all fields   |
| \<col_name1\>, \<col_name2\>, ..| specific field(s)|
| DISTINCT | only unique entries|
| COUNT(\<col_name1\>) | number of non-empty entries|
| AVG(\<col_name1\>) | mean of entries in field|

### WHERE Statement

### GROUPBY Statement

### HAVING Statement

### ORDER BY Statement

Test link: 
* [SQL Alchemy]{:.heading.flip-title} --- Unsorted notes for quick typing.
* [Python]{:.heading.flip-title} --- A snake that does not bite.
* [SQL]{:.heading.flip-title} --- From queries to ...?
* [Concepts]{:.heading.flip-title} --- None-code like data warehousing or DBMS concepts.
* [Science]{:.heading.flip-title} --- Anything theoretical from stats & causal inference to applied research.
{:.related-posts.faded}

[SQL Alchemy]: sqlalchemy.md
[Python]: py.md
[SQL]: SQL.md
[Concepts]: concepts.md
[Science]: science.md
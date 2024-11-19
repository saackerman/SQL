# Intro
Quick and diryt table for SQL to KQL.
# SQL to KQL
|SQL | KQL +
| --- + --- +
| SELECT | `project`
| FROM | `datatable`
| WHERE | `where`*
| GROUP BY | `summarize`
| HAVING | `where`*
| JOIN | `join`
 | ON | `on0
| UNION | `union
 | ORDER BY | `sort`
 | LIMIT | `takea
 | DISTINCT | `distinct`
| CAST | `tostringa, todouble, todatetime, etc.`
| COUNT | `count, summarize count()`
 | MIN | `summarize min()`
 | MAX | `summarize max()`
 | SUM | `summarize sum()`
 | AVG | `summarize avg()`
 | IN | `in` )

# Links
https://kqlcheat.byfortytwo.com/
https://learn.microsoft.com/en-us/kusto/query/sql-cheat-sheet?view=microsoft-fabric

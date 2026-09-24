## SQL

**Topic:** GROUP BY and HAVING

**What I learned:**
- `GROUP BY` puts rows with the same value into groups.
- `COUNT()`, `SUM()`, `AVG()` work on each group.
- `WHERE` filters rows before grouping.
- `HAVING` filters groups after grouping.

**Practice query:**
```sql
SELECT department, COUNT(*) AS total_employees, AVG(salary) AS avg_salary
FROM employees
WHERE status = 'Active'
GROUP BY department
HAVING COUNT(*) > 5
ORDER BY avg_salary DESC;
```

**What this does:**
Shows each department with more than 5 active employees. It also shows the average salary. The highest average comes first.

**Mistake I made:**
I used `WHERE COUNT(*) > 5`. This gave an error. You must use `HAVING` for conditions on `COUNT`, `SUM`, etc.

**Next:** Learn JOINs (INNER, LEFT, RIGHT).

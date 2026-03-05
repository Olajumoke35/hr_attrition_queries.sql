# hr_attrition_queries.sql
-- Attrition by department SELECT Department, COUNT(EmployeeID) AS TotalEmployees, SUM(CASE WHEN Attrition='Yes' THEN 1 ELSE 0 END) AS EmployeesLeft FROM employees GROUP BY Department;  -- Average salary by job role SELECT JobRole, AVG(MonthlyIncome) AS AvgSalary FROM employees GROUP BY JobRole;

-- Write a SQL query to find the average salary for each department and also include the total number of employees 
-- in each department. Display the results in descending order of the average salary.
Select department_name, avg(salary) as average_salary, count(*) as total_employees
from employees e join departments d on e.department_id = d.department_id
group by d.department_id
order by average_salary desc;

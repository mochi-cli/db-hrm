---
mochi_example: hrm_records.v1
---

# HRM Sample Records

This file shows the data shape for the HRM template tables.

## Departments

| id | department_id | department_name | manager_id | location |
|---|---:|---|---:|---|
| dept_people | 1 | People Operations | 1 | New York |
| dept_finance | 2 | Finance |  | San Francisco |

## Jobs

| id | job_id | job_title | min_salary | max_salary |
|---|---:|---|---:|---:|
| job_hr_manager | 1 | HR Manager | 65000.00 | 95000.00 |
| job_payroll_specialist | 2 | Payroll Specialist | 52000.00 | 78000.00 |

## Employees

| id | employee_id | first_name | last_name | email | phone_number | hire_date | job_id | department_id | manager_id | salary | status |
|---|---:|---|---|---|---|---|---:|---:|---:|---:|---|
| emp_alex | 1 | Alex | Carter | alex.carter@example.com | (212) 555-0147 | 2026-01-15 | 1 | 1 |  | 85000.00 | Active |
| emp_maya | 2 | Maya | Collins | maya.collins@example.com | (415) 555-0198 | 2026-02-01 | 2 | 2 | 1 | 70000.00 | Active |

## Attendance

| id | attendance_id | employee_id | work_date | clock_in | clock_out | status |
|---|---:|---:|---|---|---|---|
| attendance_001 | 1 | 1 | 2026-07-12 | 2026-07-12T09:00:00 | 2026-07-12T17:30:00 | Present |

## Payroll

| id | payroll_id | employee_id | payment_date | gross_salary | deductions | net_salary | payment_method |
|---|---:|---:|---|---:|---:|---:|---|
| payroll_001 | 1 | 1 | 2026-07-31 | 7083.33 | 500.00 | 6583.33 | Bank Transfer |

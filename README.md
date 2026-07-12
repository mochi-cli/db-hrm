# Mochi HRM Template

This repository defines the `hrm` MochiKit workspace template.

## Tables

- `Departments`
- `Jobs`
- `Employees`
- `Attendance`
- `Payroll`

## Relationships

- Departments can reference an employee as manager.
- Employees belong to a job and can belong to a department.
- Employees can reference another employee as manager.
- Attendance belongs to employees.
- Payroll belongs to employees.

## Use

```bash
mochikit init --template hrm
```

MochiKit reads this template through its template registry.

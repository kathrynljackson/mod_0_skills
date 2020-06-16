# class_1.md


## Class: Employee


### Attributes

`posFeedback` (integer): how many positive feedback comments have been received from customers about this employee

`hoursWorked` (integer): how many unpaid hours have been worked so far by this employee

`workHoursToday` (integer): how many hours this employee worked today

`managerStatus` (Boolean): whether or not the employee is a manager, true = manager, false = employee



### Methods

`posFeedbackAdd` (modifies `posFeedback`; increases `posFeedback` value by 1)

`promote`(modifies `managerStatus`; if value = `false`, change value to `true`)

`enterHours` (uses `hoursWorked` and `workHoursToday`; adds the value of the two attributes)

`calcVacation` (uses `hoursWorked` and `workHoursToday`; adds the value of the two attributes, then multiplies product by 0.025 to return the number of vacation days collected by that employee)

The Employee class inherits from the ABC , abstract base class thus it is an Abstract class
   -it has three attributes emp_id , name, salary
   -it declares calculate_salary as abstract method by using @abstractmethod
Subclass HourlyEmployee and SalariedEmployee inherit from the Abstract class Employee
HourlyEmployee 
  -has additional attributes hourly_rate and hours_worked
  -it implements calculate_salary by multiplying hourly_rate by hours_worked
SalariedEmployee 
  -has additional attribute monthly salary
  -it implements calculate_salary by providing monthly salary

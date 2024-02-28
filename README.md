**Part 1**
This Java project provides a simple implementation for calculating the area and perimeter of three geometric shapes: Circle, Triangle, and Rectangle. The project is organized into a set of classes following the principles of object-oriented programming.

Classes

Shape Interface:
    Interface defining two methods: calculateArea() and calculatePerimeter() to be implemented by shape classes.
    Includes a constant PI for mathematical calculations involving the circle.
Circle Class:
    Represents a circle with a specified radius.
    Implements the Shape interface.
    Utilizes the formulae for circle area and perimeter.
Triangle Class:
    Represents a triangle with three specified sides.
    Implements the Shape interface.
    Calculates the area using Heron's formula and perimeter as the sum of sides.
Rectangle Class:
    Represents a rectangle with specified length and width.
    Implements the Shape interface.
    Calculates area and perimeter based on length and width.


**Part 2**
This Java project is designed to facilitate employee payroll management, accommodating both regular and bonus employees. The system is organized into classes that encapsulate employee details, salary components, and payroll processing.

Employee Class
The Employee class serves as the abstract base class, capturing essential attributes such as name, designation, department, bank details, and various identifiers. It includes methods for setting and retrieving employee details, calculating monthly salaries, and handling bonus-related functionalities.
  Key Methods:
      theMonthly(): An abstract method defining the common structure for monthly salary calculation. Subclasses must implement this method with specific logic for earnings, deductions, and net salary.
      NormalEmployee Class
      The NormalEmployee class extends the Employee class, implementing the theMonthly() method with specific logic for regular employees. It calculates earnings based on basic wage, HRA, conveyance allowance, and more. Deductions include EPF, ESI, Professional Tax, and loan recovery.

NormalEmployee Class
The NormalEmployee class extends the Employee class, implementing the theMonthly() method with specific logic for regular employees. It calculates earnings based on basic wage, HRA, conveyance allowance, and more. Deductions include EPF, ESI, Professional Tax, and loan recovery.
  Key Methods:
      theMonthly(): Implements the abstract method from the Employee class, providing detailed logic for calculating monthly salary for normal employees.
      BonusEmployee Class
      The BonusEmployee class, also extending Employee, introduces a bonus component. It inherits the earnings and deductions logic from the parent class and incorporates bonus calculations, influencing the net salary.

  Usage :
      Create an instance of NormalEmployee.
      Set employee details, working days, and other parameters.
      Call the theMonthly() method to compute the monthly salary.
      Print the pay slip using the printPaySlip() method.
  
BonusEmployee Class
The BonusEmployee class, also extending Employee, introduces a bonus component. It inherits the earnings and deductions logic from the parent class and incorporates bonus calculations, influencing the net salary.
  Key Methods:
    theMonthly(): Overrides the method from the Employee class to include bonus calculations in the monthly salary.
    PaySlip Class
    The PaySlip class contains the main method, demonstrating the functionality of the payroll system. It creates instances of both NormalEmployee and BonusEmployee, sets their attributes, and computes their monthly salaries.

  Usage :
    Create an instance of BonusEmployee.
    Set employee details, working days, bonus percentage, and other parameters.
    Call the theMonthly() method to compute the monthly salary with bonus.
    Print the pay slip using the printPaySlip() method.

    
PaySlip Class
The PaySlip class contains the main method, demonstrating the functionality of the payroll system. It creates instances of both NormalEmployee and BonusEmployee, sets their attributes, and computes their monthly salaries.
  Key Methods:
    main(): Illustrates the usage of the employee classes, creating instances, setting parameters, and printing detailed pay slips.

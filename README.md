# JAVA_RECORD_4
LAB 4 – Interfaces and Polymorphism in Java
Object Oriented Programming with Java (OOPS Java)
Student Details
Name: Punith C
USN: 1BF25CS196
College: BMS College of Engineering
Lab: 4
Topic: Interfaces, Implementing Classes and Polymorphism
1. Introduction
This lab demonstrates the concepts of Interfaces and Polymorphism in Java through three different programs.

The programs show how multiple classes can implement the same interface and provide their own implementations of interface methods.

Concepts Covered
Interfaces
Implementing interfaces using implements
Inheritance using extends
Constructors and super()
Runtime polymorphism
Interface reference variables
Method overriding
2. Programs Included
Program 1: Parking Charge (ParkingDemo.java)
Aim: To calculate parking charges for different vehicles using an interface, inheritance and polymorphism.

Classes and Interface:

ParkingCharge – Interface containing calculateCharge() and displayParkingDetails().
VehicleParking – Parent class containing common vehicle details.
TwoWheeler – Calculates parking charges for two-wheelers.
FourWheeler – Calculates parking charges for four-wheelers.
ParkingDemo – Main class to execute the program.
Parking Charges:

Two-wheeler: Rs. 20 per hour for the first two hours and Rs. 10 for each additional hour.
Four-wheeler: Rs. 50 per hour for the first two hours and Rs. 30 for each additional hour.
Expected Output:

Two-wheeler (4 hours): Rs. 60.0
Four-wheeler (5 hours): Rs. 190.0
Program 2: Payment Methods (Pay.java)
Aim: To demonstrate how one interface can be implemented by different payment methods.

Classes and Interface:

Payment – Interface containing pay(double amount).
CreditCardPayment – Implements the Payment interface.
UPIPayment – Implements the Payment interface.
PayPalPayment – Implements the Payment interface.
Pay – Main class.
Expected Output:

Amount: 100.0
Amount: 200.0
Amount: 300.0
Program 3: Employee Salary (SalaryEmployee.java)
Aim: To calculate the salaries of different types of employees using an interface.

Classes and Interface:

Salary – Interface containing calculateSalary().
PermanentEmployee – Calculates salary using basic salary and allowance.
ContractEmployee – Calculates salary using working days and daily wages.
SalaryEmployee – Main class.
Salary Calculation:

Permanent Employee: 30000 + 5000 = Rs. 35000.0
Contract Employee: 20 × 800 = Rs. 16000.0
Expected Output:

Salary :35000.0
Salary :16000.0
3. How to Compile and Run
Make sure Java JDK is installed on your system.

Open the terminal or command prompt in the directory containing the Java files.

Program 1
javac ParkingDemo.java
java ParkingDemo
Program 2
javac Pay.java
java Pay
Program 3
javac SalaryEmployee.java
java SalaryEmployee
4. Important Note
The public class name must match the Java filename.

For example:

ParkingDemo.java → ParkingDemo
Pay.java → Pay
SalaryEmployee.java → SalaryEmployee
In Program 3, a duplicate class error occurred when the interface and public class were both named Salary. It was resolved by renaming the public class to SalaryEmployee.

5. Conclusion
This lab demonstrates how interfaces provide a common structure for different classes and how polymorphism allows the same interface reference to work with different objects.

The three programs illustrate the practical applications of interfaces and runtime polymorphism in Java.

End of LAB 4 – Interfaces and Polymorphism in Java

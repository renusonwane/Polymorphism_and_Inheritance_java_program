# Polymorphism_and_Inheritance_java_program

Part 1: Exploring the HR System
Download the src folder and import the project into IntelliJ Idea
In this exercise, we'll create the Human Resources Management System mentioned in the theory section
Create the following class


Implement the methods:

   public int timeToRetirement(){
      // time to retirement = min(60 - age, 40 - yearsWorked)
   }

   public int vacationTimeLeft(){
       // vacation time left = (daysWorked/360)*(30 - vacationDaysTaken)
   }

   public int calculateBonus(){
       // bonus = 2.2*salary
   }
Now, create a sales rep class that inherits the original employee class
The arrow used means inheritance in class diagrams


   public int calculateComission(){
      // comission = 0.1 * salesMade
   }
Create a Java Class for sales manager:


   public void calculateComission(){
      // 0.03 * all sales made by team
   }
Run the main method and verify that your implementation works.

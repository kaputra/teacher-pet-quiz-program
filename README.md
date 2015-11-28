// ************************************************************
// Student.java
//
// Define a student class that stores name, score on test 1, and
// score on test 2. Methods prompt for and read in grades,
// compute the average, and return a string containing student's info.
// ************************************************************
import java.util.Scanner;

public class Student
{
//declare instance data
	String name;
	int grade;
	Scanner scan = new Scanner(System.in);
// ---------------------------------------------
//constructor
// ---------------------------------------------
public Student(String studentName)
{
	studentName = scan.nextLine();
	name = studentName;

}

// ---------------------------------------------
//inputGrades: prompt for and read in student's grades for test1 and test2.
//Use name in prompts, e.g., "Enter's Joe's score for test1".
// ---------------------------------------------
public void inputGradeAverage()
{
	System.out.println("Enter " + name + "'s grade average: ");
	grade = scan.nextInt();
}

// ---------------------------------------------
//getAverage: compute and return the student's test average
// ---------------------------------------------
public double getAverage(double average)
{
	average = grade;
	return average;
}

// ---------------------------------------------
//getName: print the student's name
// ---------------------------------------------
public String getName()
{
	return name;
}

public String toString()
	{
		System.out.println("Name: " + name + "grade: " + grade);
	}
}}


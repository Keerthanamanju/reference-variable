# reference-variable
   import java.util.Scanner;

class Student {
    // Fields
    int rollNumber;
    String name;
    double marks;
}


  
    // Constructor
    public Student(int rollNumber, String name, double marks) {
        this.rollNumber = rollNumber;
        this.name = name;
        this.marks = marks;

class Student {
    // Fields
    int rollNumber;
    String name;
    double marks;


    // Method to display student details
    public void displayDetails() {
        System.out.println("Student Details:");
        System.out.println("Roll Number: " + rollNumber);
        System.out.println("Name: " + name);
        System.out.println("Marks: " + marks);
    }
}
 // Displaying details using the reference variable
        student1.displayDetails();

        // Taking input for the second student
        System.out.println("\nEnter details for Student 2:");
        System.out.print("Enter Roll Number for Student 2: ");
        int rollNumber2 = scanner.nextInt();
        scanner.nextLine(); // Consume newline
        System.out.print("Enter Name for Student 2: ");
        String name2 = scanner.nextLine();
        System.out.print("Enter Marks for Student 2: ");
        double marks2 = scanner.nextDouble();


public class ReferenceVariableExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Taking input for the first student
        System.out.print("Enter Roll Number for Student 1: ");
        int rollNumber1 = scanner.nextInt();
        scanner.nextLine(); // Consume newline
        System.out.print("Enter Name for Student 1: ");
        String name1 = scanner.nextLine();
        System.out.print("Enter Marks for Student 1: ");
        double marks1 = scanner.nextDouble();

        // Creating a Student object (reference variable)
        Student student1 = new Student(rollNumber1, name1

        // Creating another Student object (reference variable)
        Student student2 = new Student(rollNumber2, name2, marks2);

        // Displaying details using the reference variable
        student2.displayDetails();

        scanner.close();
    }
}


OUTPUT:
Enter Roll Number for Student 1: 101
Enter Name for Student 1: Alice
Enter Marks for Student 1: 88.5

Student Details:
Roll Number: 101
Name: Alice
Marks: 88.5

Enter Roll Number for Student 2: 102
Enter Name for Student 2: Bob
Enter Marks for Student 2: 92.0

Student Details:
Roll Number: 102
Name: Bob
Marks: 92.0

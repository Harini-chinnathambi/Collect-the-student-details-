# Collect-the-student-details-
import java.util.Scanner;

public class StudentDetails {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Collect student details
        System.out.print("Enter Student Name: ");
        String name = scanner.nextLine();

        System.out.print("Enter Student Age: ");
        int age = scanner.nextInt();

        System.out.print("Enter Student Grade: ");
        String grade = scanner.next();

        // Display the collected details
        System.out.println("\nStudent Details:");
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Grade: " + grade);

        scanner.close();
    }
}
Output:
Enter Student Name: Alice
Enter Student Age: 20
Enter Student Grade: A

Student Details:
Name: Alice
Age: 20
Grade: A

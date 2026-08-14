# Student-details-import java.util.Scanner;

public class CourseRegistration {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter Student Name: ");
        String name = sc.nextLine();

        System.out.print("Enter Student ID: ");
        int id = sc.nextInt();
        sc.nextLine();

        System.out.print("Enter Department: ");
        String department = sc.nextLine();

        System.out.print("Enter Course: ");
        String course = sc.nextLine();

        System.out.print("Enter Database Name: ");
        String database = sc.nextLine();

        System.out.println("\n--- Course Registration ---");
        System.out.println("Name       : " + name);
        System.out.println("ID         : " + id);
        System.out.println("Department : " + department);
        System.out.println("Course     : " + course);
        System.out.println("Database   : " + database);

        sc.close();
    }
}

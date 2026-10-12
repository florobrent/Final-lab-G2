# Final-lab-G2

package com.mycompany.studentgradecalculators;

public class StudentGradeCalculators {

    public static void main(String[] args) {

        java.util.Scanner input =
                new java.util.Scanner(System.in);

        System.out.print("Student Name: ");
        String name = input.nextLine();

        System.out.print("Grade 1: ");
        double grade1 = input.nextDouble();

        System.out.print("Grade 2: ");
        double grade2 = input.nextDouble();

        System.out.print("Grade 3: ");
        double grade3 = input.nextDouble();

        double average = (grade1 + grade2 + grade3) / 3.0;

        System.out.println();
        System.out.println("=== STUDENT RESULT ===");
        System.out.println("Student Name: " + name);
        System.out.printf("Average: %.2f%n", average);

        if (average >= 75) {
            System.out.println("Status: Passed");
        } else {
            System.out.println("Status: Failed");
        }

        

    }
}

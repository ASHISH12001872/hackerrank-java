import java.util.ArrayList;
import java.util.List;
import java.util.Scanner;
import java.util.function.Predicate;

class Student {
  String name;
  int rollNo;
  String department;

  public Student(String name, int rollNo, String department) {
    this.name = name;
    this.rollNo = rollNo;
    this.department = department;
  }
}

@FunctionalInterface
interface StudentPredicate {
  boolean test(Student s);
}

public class Main {
  public static void main(String[] args) {
    Scanner scanner = new Scanner(System.in);
    int numStudents = scanner.nextInt();

    if (numStudents <= 1) {
      System.out.println("Invalid");
      return;
    }

    List<Student> students = new ArrayList<>();
    for (int i = 1; i <= numStudents; i++) {
      String name = scanner.next();

      int rollNo = scanner.nextInt();

      String department = scanner.next();

      students.add(new Student(name, rollNo, department));
    }

    StudentPredicate csePredicate = s -> s.department.equals("CSE");
    for (Student s : students) {
      if (csePredicate.test(s)) {
        System.out.println(s.rollNo);
      }
    }
  }
}

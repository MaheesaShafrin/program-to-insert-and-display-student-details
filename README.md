# program-to-insert-and-display-student-details
import java.util.Scanner;
class Student {
String name;
int age;
public void insertDetails(String name, int age) {
this.name = name;
this.age = age;
}
public void displayDetails() {
System.out.println(&quot;Name: &quot; + name);
System.out.println(&quot;Age: &quot; + age);
}
}
public class StudentDetailsExample {
public static void main(String[] args) {
Scanner sc = new Scanner(System.in);
Student student = new Student();
System.out.print(&quot;Enter name: &quot;);
String name = sc.nextLine();
System.out.print(&quot;Enter age: &quot;);
int age = sc.nextInt();
student.insertDetails(name, age);
student.displayDetails();
}
}
Output
Enter name: Monish
Enter age: 21

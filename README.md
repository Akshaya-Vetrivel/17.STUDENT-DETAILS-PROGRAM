# 17.STUDENT-DETAILS-PROGRAM
package student;
import java.util.Scanner;
class candidates{
    String name;
    int age;
    int marks;
    public void inputDetails(){
        Scanner sc =new Scanner(System.in);
        System.out.println(" Enter Student name:" );
        name=sc.nextLine();
        System.out.println("Enter Student Age:" );
        age=sc.nextInt();
        System.out.println("Enter Student marks:");
        marks=sc.nextInt();
    }
    public void displayDetails(){
        System.out.println("student name:" +name);
        System.out.println("age:" +age);
        System.out.println("marks:" +marks);
    }
}
public class Student {

    public static void main(String[] args) {
        // TODO code application logic here
        candidates s = new candidates();
        s.inputDetails();
        s.displayDetails();
        
        
    }
    
}

O/P

run:
Enter Student name:
Akshays
Enter Student Age:
18
Enter Student marks:
98
student name:Akshays
age:18
marks:98
BUILD SUCCESSFUL (total time: 22 seconds)


# Let-s-Code-loop-in-JAVA
# Using if-else loop in JAVA to code for grading.
import java.until.Scanner;
public class Decision making{
public static void main(String[] args){
  int input;
  System.out.println("Enter your marks : ");
  Scanner s = new Scanner(System.in);
  input = s.nextInt();
  if(input > 80)
   System.out.println("A Grade");
  else if(input > 70)
   System.out.println("B Grade");
  else if(input > 60)
   System.out.println("C Grade");
  else if(input > 40)
   System.out.println("D Grade");
  else
   System.out.println("Fail");
}
}

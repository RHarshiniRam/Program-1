import java.util.Scanner;
public class EvenOdd
{

  public static void main(String[] args) 
  {

    Scanner sc = new Scanner(System.in);
    int i;
    System.out.println("Enter a number:");
    i=sc.nextInt();
    if (i % 2==0)
      System.out.println("the entered number is even");
    else
      System.out.println("the entered number is odd:");
  }
}

import java.util.Scanner;

public class Calculator {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);
    System.out.println("===CALCULATOR===");
     System.out.println("1. Multiplication");
      System.out.print("Enter: ");
      int input = sc.nextInt();
      System.out.print("Enter number: ");
      int num1 = sc.nextInt();
      System.out.print("Enter number: ");
      int num2 = sc.nextInt();

      switch (input){
      case 1 :
        int mul = num1 * num2 ;
        System.out.println("Total: " + mul);
        break;
      default :
        System.out.println("Invalid input");
        }
      }
    }
  

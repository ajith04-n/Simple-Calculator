import java.util.Scanner;
public class Main{
    public static void main (String []args)
    {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Enter 1st number");
        int num1 = scanner.nextInt();
        System.out.println("enter 2nd number");
        int num2 = scanner.nextInt();

        System.out.println("1.Addition");
        System.out.println("2.Subration");
        System.out.println("3.Multiplication");
        System.out.println("4.Division");
        int op = scanner.nextInt();

        switch(op)
        {
            case 1:
            System.out.println("Addition:-"+(num1+num2));
            break;
            case 2:
            System.out.println("Subtration:-"+(num1-num2));
            break;
            case 3:
            System.out.println("Multiplication:-"+(num1*num2));
            break;
            case 4:
            System.out.println("Division:-"+(num1/num2));
            break;
 
        }
        scanner.close();
    }
}

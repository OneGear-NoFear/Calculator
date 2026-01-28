import java.util.Scanner;
public class MDASgroup {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        //Result
        int res = ' ';

        System.out.println("-----MDAS Assignment.-----");
        
        //Inputting numbers
        System.out.print("Enter 1st number: ");
        int num1 = sc.nextInt();
        System.out.print("Enter 2nd number: ");
        int num2 = sc.nextInt();
        
        //Choosing an operator
        System.out.println("Choose one operator: (+, -, *)");
        char op = sc.next().charAt(0);

        switch(op){
            case '+':
                res = num1 + num2;
                System.out.println(num1 + " + " + num2 + " = " + res);
                break;

            default:
                System.out.println("Invalid input...");
                break;
        }
        
    }
    
}

 import java.util.Scanner;

public class MDASAssignment {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);
        int res;

        System.out.println("-----MDAS Assignment-----");

        // Inputting numbers
        System.out.print("Enter 1st number: ");
        int num1 = sc.nextInt();

        System.out.print("Enter 2nd number: ");
        int num2 = sc.nextInt();

        // Choosing an operator
        System.out.println("Choose one operator: (-)");
        char op = sc.next().charAt(0);

        switch (op) {
            case '-':
                res = num1 - num2;
                System.out.println(num1 + " - " + num2 + " = " + res);
                break;

            default:
                System.out.println("Invalid input...");
                break;
        }

        sc.close();
    }

import java.util.Scanner;
public class MDASgroup {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        //Result
        int res = ' ';

        System.out.println("-----MDAS Assignment.-----");
        
        //Inputting numbers
        System.out.print("Enter 1st number: ");
        int num1 = sc.nextInt();
        System.out.print("Enter 2nd number: ");
        int num2 = sc.nextInt();
        
        //Choosing an operator
        System.out.println("Choose one operator: (+, -, *)");
        char op = sc.next().charAt(0);

        switch(op){
            case '*':
                res = num1 * num2;
                System.out.println(num1 + " + " + num2 + " = " + res);
                break;

            default:
                System.out.println("Invalid input...");
                break;
        }
        
    }
    
}


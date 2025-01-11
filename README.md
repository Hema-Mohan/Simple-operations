# Simple-operations
import java.util.Scanner;
Public class simpleoperations {
    
    Public static void main(String[]args){
      
    Scanner sc = new Scanner(System.in);
        System.out.print("Enter 1st number:");
        int n1= sc.nextInt();
        System.out.print("Enter 2nd number:");
        int n2= sc.nextInt();
        System.out.print("Enter 3rd number:");
        int n3= sc.nextInt();
        // ARITHMETIC OPERATORS
        System.out.println("\n----Arithmetic Operations-----\n");
        System.out.println("ADDITION = " + (n1+n2+n3));
        System.out.println("SUBTRACTION = " + (n2-n3));
        System.out.println("MULTIPLICATION = " + (n1*n2*n3));
        System.out.println("DIVISION = " + (n1/n3));
        System.out.println("MODULUS = " + (n1%n2));
        // RELATIONAL OPERATORS
        System.out.println("\n-----Relational Operations-----\n");
        System.out.println(" Greater than = " + (n1>n2));
        System.out.println(" Less than = " + (n2<n3));
        System.out.println(" Equal to = " + (n1==n3));
        System.out.println(" Not equal to = " + (n1!=n2));
        // LOGICAL OPERATORS
        System.out.println("\n-----Logical Operations------\n");
        System.out.println("And operator = " + ((n1>n2)&&(n1>n3)));
        System.out.println("Or operator = " + ((n1>n2)||(n1>n3)));
        System.out.println("Not operator = " + (!(n1>n2)));
        // TERNARY OR CONDITIONAL OPERATOR
        System.out.println("\n-----Ternary Operation----\n");
        String result = (n1> n2)? " n1 is greater than n2 " : " n1 is not greater than n2 ";
        System.out.println("Result : " + result);
    }
}

OUTPUT:

Enter 1st number:15
Enter 2nd number:10
Enter 3rd number:5

----Arithmetic Operations-----

ADDITION = 30
SUBTRACTION = 5
MULTIPLICATION = 750
DIVISION = 3
MODULUS = 5

-----Relational Operations-----

 Greater than = true
 Less than = false
 Equal to = false
 Not equal to = true

-----Logical Operations------

And operator = true
Or operator = true
Not operator = false

-----Ternary Operation----

Result :  n1 is greater than n2


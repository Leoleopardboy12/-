# -
Class tasks
17-05-2019

package javaapplication1;
import java.util.Scanner;

public class JavaApplication1 {

   
    public static void main(String[] args) {
        // TODO code application logic here
        System.out.println("Enter day...");
        Scanner inpt = new Scanner(System.in);
        int day = inpt.nextInt();
        System.out.println("Enter month...");
        Scanner inptm = new Scanner(System.in);
        int month = inptm.nextInt();
        System.out.println("Enter year...");
        Scanner inpty = new Scanner(System.in);
        String year = inpty.nextLine();
        
        System.out.println("The date is " + day + "-"+ month + "-"+ year);
        
      
    }
    
}

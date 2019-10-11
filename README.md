# -
Class tasks
17-05-2019
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

package javaapplication1;
import java.util.Scanner;
/**
 *
 * @author 1
 */
public class JavaApplication1 {

    /**
     * @param args the command line arguments
     */
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
        
       // int d > 31;
      // int day = d
//int month = >0<=12;
//int year =2019 ;
//String date = d-month-year;
//System.out.println(String data);

    }
    
}

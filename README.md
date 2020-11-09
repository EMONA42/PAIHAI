/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

package javaapplication9;

/**
 *
 * @author Wow =0= yiiooo
 */
import java.util.Scanner;//Import the Scanner class 
public class JavaApplication9 {

    /**
     * @param args the command line arguments
     */
   
    public static void main(String[] args) {
        // TODO code application logic here
    Scanner myObj = new Scanner(System.in);//Create a object
        //  ask user to input number
    System.out.println("Hours:");

    String number = myObj.nextLine();
    int hours = Integer.parseInt(number);

        //calulation
    int hrWeek = hours *5;
    int hrYeark = hours *252;


         //display output
    System.out.println ("The hours in 5-day wk is："+hrWeek );
    System.out.println ("The hours on 252-day work yk is： "+hrYeark );       
    }

}

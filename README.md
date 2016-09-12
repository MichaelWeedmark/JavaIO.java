# JavaIO.java
/****************************************************************************
 *
 *
 *
 *
 *
 *
 ****************************************************************************/

import java.util.Scanner;


class Main {
  public static void main(String[] args) {
    System.out.println("Please enter the food type (pizza, sub, soup)");
    
    Scanner input = new Scanner(System.in);

     final String FoodType = input.nextLine();
     final double time;
     final String Sub = "sub";
     final String Pizza = "pizza";
     final String Soup = "soup";
    
    if (FoodType == Sub){
    	
    	time = 1;
    	System.out.println("Sub: Please enter the amount of subs");
    }
    
  }
}

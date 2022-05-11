# Section-C
Option 1: Say the Number
Java language was used to implement the solution

import java.util.*;

public class ChallengeC {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
      int input=0;
      Scanner answer= new Scanner(System.in);
      
      System.out.println("please Note the following system is programmed"
    		  +"\nTo accept numerical values and return a starndard way of reading a number."
    		  +"\nType in a numerical digit between 1 - 12\n");
      
      System.out.println("please enter any numerical value of your choice");
      input=answer.nextInt();
      
    if(input ==0)
    {
    	System.out.println("zero.");
    }
    else if (input ==1)
    {
    	System.out.println("One.");
    }
    else if (input ==2)
    {
    	System.out.println("Two.");
    }
    else if (input ==3)
    {
    	System.out.println("Three.");
    }
    else if (input ==4)
    {
    	System.out.println("Four.");
    }
    else if (input ==5)
    {
    	System.out.println("Five.");
    }
    else if (input ==6)
    {
    	System.out.println("six.");
    }
    else if (input ==7)
    {
    	System.out.println("Seven.");
    }
    else if (input ==8)
    {
    	System.out.println("Eight.");
    }
    else if (input ==9)
    {
    	System.out.println("Nine.");
    }
    else if (input ==10)
    {
    	System.out.println("Ten.");
    }
    else if (input ==11)
    {
    	System.out.println("Eleven.");
    }
    else if (input ==12)
    {
    	System.out.println("Twelve.");
    }
    else
    {
    	System.out.println("The number is out of the range "+
    "\nPlease run the program again.");
    }
	}

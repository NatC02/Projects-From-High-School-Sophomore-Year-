//(c) A+ Computer Science
// www.apluscompsci.com

//OOP example

public class Triangle
{
	//instance variables
   private int sideA, sideB, sideC;

   public Triangle()
   {
      sideA = 0;
      sideB = 0;
      sideC = 0;
   }

   public Triangle(int a, int b, int c)
   {
      //add the needed code to this method

   }

   public void setSides(int a, int b, int c)
   {
   	sideA=a;
   	sideB=b;
   	sideC=c;
   }
   
   public void print()
   {
   	  System.out.println( "" + sideA + " " + sideB + " " + sideC );
   }
   
   //either of these can be used to print out the Triangle

   public String toString()
   {
   	 return "" + sideA + " " + sideB + " " + sideC;
   }
}
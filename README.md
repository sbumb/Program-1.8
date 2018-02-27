# Program-1.8
Intro to Java Programming, Comprehensive Version, 10th Edition, Y. Daniel Liang

Question:

        (Area and perimeter of a circle) Write a program that displays the area and perimeter of a circle 
		that has a radius of 5.5 using the following formula: 
                                        perimeter = 2 * radius * pi
                                        area = radius * radius * 
                                        
Code:

        public class s_1_8 {
	
		      public static void main (String args[]){
			
			      double radius = 5.5;
			      double PI = 3.14;
			      double perimeter = 2 * radius * PI;
			      double area = radius * radius * PI;
			
			    System.out.println(perimeter);
			    System.out.println(area);
			  }
	
    }

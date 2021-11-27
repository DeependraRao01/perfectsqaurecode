# perfectsqaurecode


import java.util.Scanner;
public class perfectSquare 
{
	public static void main(String[] args) {
	  Scanner sc=new Scanner(System.in);
	  System.out.println("Enter a number");
	  int number=sc.nextInt();
	  double x=Math.sqrt(number);
	  if(x==(int)x)
	  {
		System.out.println("Given number is perfect sqaure");
	  }
	  else
	  {
		System.out.println("Given number is not a perfect square");
		
	}

	}
}

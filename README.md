# addition
package gunaaexercise;

import java.util.Scanner;

public class add
{
	public static void main(String args[])
	{
		int a,b,c;
		Scanner sc=new Scanner(System.in);
		System.out.println("Enter the values");
		a=sc.nextInt();
		b=sc.nextInt();
		c=a+b;
		System.out.println("The sum is "+c);
	}
}

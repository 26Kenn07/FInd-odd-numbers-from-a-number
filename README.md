# FInd-odd-numbers-from-a-number
How to find odd number from a number


package pp;

import java.util.Scanner;
public class Num {
	
	public static void main(String[] args)
	{
		Scanner sc = new Scanner(System.in);
		
		long x = sc.nextInt();
		long[] y = new long[10];

		
		while(x>0)
		{
			for(int i=0;i<10;i++) 
			{
				y[i] = x % 10;
		
				x = x/10;
		
	
				if(y[i]%2 != 0)
				{
					System.out.println(y[i]);
				}
			}
		}
	}

}

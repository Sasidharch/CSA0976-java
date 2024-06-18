import java.io.*; 
import java.util.Scanner;
class GCDLCM { 
	static int gcd(int a, int b) { 
		if (b == 0) 
			return a; 
		else
			return gcd(b, a % b); 
}
	static int lcm(int a, int b, int gcdValue) 
	{ 
		return Math.abs(a * b) / gcdValue; 
	} 
	public static void main(String[] args) { 

		int a, b, gcdValue;
                Scanner s=new Scanner(System.in);
		System.out.println("the a value:"); 
  		a=s.nextInt();
                System.out.println("the b value:");
		b=s.nextInt(); 
		gcdValue = gcd(a, b); 
		System.out.println("GCD = " + gcdValue); 
		System.out.println("LCM = " + lcm(a, b, gcdValue)); 
	} 
}

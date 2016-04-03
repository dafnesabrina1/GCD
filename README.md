# GCD
import java.util.Scanner;
public class EuclideanAlorith {

	public static void divisor(int a, int b){
		while (b > 0){
			int remeinder = a%b;
			a=b;
			b= remeinder;}
			System.out.print("The GCD is: "+ a);
		
		
	}
	public static void main(String[] args)
	{
		int num1= 10;
		int num2= 11;
		Scanner input= new Scanner(System.in);
		System.out.print("Give me a number: ");
		num1 = input.nextInt();
		System.out.print("Give me another number: ");
		num2 = input.nextInt();
		divisor(num1,num2);
		
	}
}

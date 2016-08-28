
import java.util.Scanner;

public class milestokm {

	public static void main(String[] args) {
		Scanner scan = new Scanner (System.in);
		System.out.println ("Enter an amount of miles to be converted to kilometers");
		double miles = scan.nextInt();
		double km = miles * 1.609344;
		System.out.println ("Number of kilometers is " + km);
	}
}

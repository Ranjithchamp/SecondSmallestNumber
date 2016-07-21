# SecondSmallestNumber

import java.util.Arrays;
import java.util.Scanner;

public class ShortNumberInArray {

	public static void main(String[] args) {
		Scanner qq = new Scanner(System.in);
		System.out.println("enter size of array");
		int nn = qq.nextInt();
		int count[] = new int[nn];
		System.out.println("enter array element");
		for (int i = 0; i < nn; i++) {
			count[i] = qq.nextInt();
		}
		Arrays.sort(count);
		System.out.println("The Second Smallest number is ");
		System.out.println(count[1]);
	}

}

package monday;

import java.util.Scanner;

public class loops {

	public static void main(String[] args) {
			int num;
			int r=0;
			Scanner sc=new Scanner(System.in);
			num=sc.nextInt();
			
			
			while(num>0){
				r=num%10;
				num=num/10;
				
				System.out.println(r +" "+num);
			}
	}

}

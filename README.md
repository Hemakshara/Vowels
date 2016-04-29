# Vowels

package programs;

import java.util.Scanner;

public class vowels {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		//String a,e,i,o,u,A,E,I,O,U;
		//String s= " Hello";
		int a= 0;
		//String s ="";
		char s;
		System.out.println("Enter The String :");
		Scanner sc = new Scanner(System.in);
		String s1 = sc.nextLine();
		for(int i=0; i<s1.length();i++)
		{
		s=s1.charAt(i);
		
		
		if(s =='a' || s== 'e' || s == 'i' || s == 'o'|| s == 'u'|| s == 'A' || s=='E' || s == 'I'|| s=='O' || s =='U')
		{
			a++;
			
		}
		}	
		
		System.out.println(""+a);
		

	}

}

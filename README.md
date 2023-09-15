# StringQues1
package ss;
 import java.util.*;
 
public class StrQs1 {

	
	public static void StringOperations(String str)
	{
		int odd=0,eve=0;
		for(int i=0;i<str.length();i++)
		{
			if(i%2==0)
			{
				System.out.println(str.charAt(i));
			    eve++;
			}
			else
			{
				odd++;
			}
		}
		System.out.println("evn characters:"+eve);
		System.out.println("odd characters:"+odd);
		
	}
	public static void main(String args[])
	{   String str;
		Scanner sc = new Scanner(System.in);
		System.out.println("enter a string ");
		 str= sc.nextLine();
		StringOperations(str);
	}
	
	}

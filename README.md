# hello-world
this is a repository
public class Reverse 
{
	public static void main(String[] args) 
	{
		System.out.println("hi....");
		int number=1234;
		int revnum=0;
		int temp=0;
		while(number>0)
		{
			temp=number%10;
			revnum=(revnum*10)+temp;
			number=number/10;
		}
		System.out.println("reversed number is "+revnum);
	}
}

public class palindrome {
	public static void main(String [ ] arg){
	String name1="madAM";
	String name=name1.toUpperCase();	
	String ch="";
	for(int i=name.length()-1;i>=0;i--)
	{
		
		ch+=name.charAt(i);
		
	}

System.out.println(ch);
if(ch.equals(name))
{
	System.out.println(" palindrome");

}
else
{
	System.out.println("not palindrome");
}
	}
}


public interface A {
	static int a=5;
	final int s=3;
}

class C implements A
{
	public void display()
	{
		System.out.println(a+" "+s);
	}
}
class Jala 
{
	public static void main(String[] args){ 
			 C c = new C();
			 c.display();
		
	}
}


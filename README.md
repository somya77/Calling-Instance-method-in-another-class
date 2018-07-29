# Calling-Instance-method-in-another-class
Calling instance method in another class require to form object of that class in the main function or method then passing the value.
class Test3
{
 void disp(int a,int b)
{
 int x=a;
 int y=b;
 int z=x+y;
 System.out.println("Sum is:"+z);
}
}
class Test4
{
public static void main(String args[])
{
 Test3 obj=new Test3();
 obj.disp(15,25);
}
} 

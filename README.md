# instance-operator
instance
class s
{
int a=5,b=10;
void display()
{
int c=a+b;
System.out.println(c);
}
}

class t extends s
{
int e=11,d=12;

void display()
{
int f=e+d;
System.out.println(f);
}
}

class test
{
public static void main(String args[])
{
s t1=new s();
t1.display();
s t2=new t();
t1.display();
boolean result=t1 instanceof s; //t means false
System.out.println(result);
}
}



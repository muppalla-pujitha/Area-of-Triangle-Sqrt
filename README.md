# Area-of-Triangle-Sqrt
import java.util.Scanner;
import java.lang.*;
class triangle1
{
public static void main(String[] args)
{
int a,b,c;
float s;
double area;
Scanner sc=new Scanner(System.in);
System.out.println("enter 3 sides of triangle");
a=sc.nextInt();
b=sc.nextInt();
c=sc.nextInt();
s=(a+b+c)/2f;
area=Math.sqrt(s*(s-a)*(s-b)*(s-c));
System.out.println("Area is "+area);
}
}


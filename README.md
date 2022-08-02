# Get-Circle-Area-and-Perimeter
Q1-A2

package PQ;


public class Circle {
	double radius=1;
	double area;
	double Perimeter;
	Circle()
	{
		radius = 20;
	}
	double getarea()
	{
		area = 3.14 * radius;
		
		return area;
		
	}
	
	double getPerimeter()
	{
		Perimeter = 2 * 3.14 * radius;
		return Perimeter;
	}
	
	public static void main(String... args)
	{
		Circle C = new Circle();
		System.out.println("Area= "+C.getarea());
		System.out.println("Perimeter= "+C.getPerimeter());
	}
}

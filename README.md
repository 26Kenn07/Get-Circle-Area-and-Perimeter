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
	Circle(double r)
	{
	    radius = r;
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
		Circle C1 = new Circle();
	    
		System.out.println("Area= "+C1.getarea());
		System.out.println("Perimeter= "+C1.getPerimeter());
		
		Circle C2 = new Circle(5);
		System.out.println("Area= "+C2.getarea());
		System.out.println("Perimeter= "+C2.getPerimeter());
	}
}

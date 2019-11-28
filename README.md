# homework

```java

interface Shape
{
  abstract double getArea();
}

class Rectangle implements Shape
{
  double length;
  double width;
  
  public Rectangle(double l,double w)
  {
    length = l;
    width = w;
  }
  
  public double getArea()
  {
    double area = length*width;
    return area;
  }  
  
  public String toString()
  {
    String ans = double.toString(getArea());
    return ans;
  }
}

///
class Triangle implements Shape
{
  double base;
  double width;
  
  public Triangle(double b,double w) 
  {
    base = b;
    width = w;
  }
  
  public double getArea()
  {
    double area = base*width*0.5;
    return area;
  }
  
  public String toString()
  {
    String ans = double.toString(getArea());
    return ans;
  }
}

```

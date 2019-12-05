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
    String ans = Double.toString(getArea());
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
    String ans = Double.toString(getArea());
    return ans;
  }
}

```

![pic](irs_1575356181800ac14ecaa5b0930566fb0f3061aa4ceca584af.jfif)

```java
//JAVA code
class Student{
  Course[] courses = new Course[10];
}

class Course{
}

```

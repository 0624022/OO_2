# 0624022 顏志祐

## 0624022 顏志祐

### 0624022 顏志祐

#### 0624022 顏志祐

##### 0624022 顏志祐

###### 0624022 顏志祐

:sunny:
:zap:
:horse:
:cow2:
```你好帥```
```但我更帥```
>新北市
>>板橋區


* red
* green
* blue

***
[谷歌](https://www.google.com.tw/)

**禿子**

*跟著*

~~月亮走~~

|置左   |  置中   | 置右 |
|:------|:------:|-----:|
|1|2|3|


![我超帥](free.png "高科大")

[![Everything Is AWESOME](https://img.youtube.com/vi/StTqXEQ2l-Y/0.jpg)](https://www.youtube.com/watch?v=StTqXEQ2l-Y "Everything Is AWESOME")


```js
abstect class CShape
{
  protected String color;
  public void setColor(String str)
  {
   color=str;
  }
 
}

class CTriangle extends CShape
{
  protected double a,b,c;
  public CCircle(double a,double b,double c)
  {
  this.a=a;
  this.b=b;
  this.c=c;
  }
  public void show()
  {
   system.out.print("color="+color+",  ");
   system.out.println("area="+a*b/2);
  }
}
public class app11_1
{
  public static void main(String args[])
  {
   CTriangle tri = new CTriangle(3,4,5);
   tri.setColor("Red");
   tri.show();
  }
}
```

```js
public interface Shape
{
   double getArea();
}

public class Rectangle implements Shape {
    private double length;
   private double width;

  
   public Rectangle(double length, double width) {
      this.length = length;
      this.width = width;
   }

   @Override
   public String toString() {
      return "Rectangle[length=" + length + ",width=" + width + "]";
   }

   // Need to implement all the abstract methods defined in the interface
   @Override
   public double getArea() {
      return length * width;
   }

}
    
public class Triangle implements Shape {
   // Private member variables
   private int base;
   private int height;

   // Constructor
   public Triangle(int base, int height) {
      this.base = base;
      this.height = height;
   }

   @Override
   public String toString() {
      return "Triangle[base=" + base + ",height=" + height + "]";
   }

   // Need to implement all the abstract methods defined in the interface
   @Override
   public double getArea() {
      return 0.5 * base * height;
   }
}
```






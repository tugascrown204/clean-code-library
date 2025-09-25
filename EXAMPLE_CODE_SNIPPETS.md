# Example Code Snippets

## Python Snippet
```python
import math

def calculate_area(radius):
    return math.pi * radius ** 2

print(calculate_area(5))  # Output: 78.53981633974483
```

## Java Snippet
```java
public class Circle {
    private double radius;

    public Circle(double radius) {
        this.radius = radius;
    }

    public double calculateArea() {
        return Math.PI * radius * radius;
    }
}

Circle circle = new Circle(5);
System.out.println(circle.calculateArea());  // Output: 78.53981633974483
}
```
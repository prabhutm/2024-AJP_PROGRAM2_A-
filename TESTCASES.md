# Test Cases for Practical1.java

## Test Case 1

### Input
```java
Point p1 = new Point(0, 0);
Point p2 = new Point(4, 0);
Point p3 = new Point(4, 3);
Point p4 = new Point(0, 3);

Trapezoid trapezoid = new Trapezoid(p1, p2, p3, p4);
Rectangle rectangle = new Rectangle(p1, p2, p3, p4);
Square square = new Square(p1, 3);
```

### Expected Output
```
Area of trapezoid=12.0
Area of rectangle=12.0
Area of square=9.0
```

---

## Test Case 2

### Input
```java
Point p1 = new Point(0, 0);
Point p2 = new Point(8, 0);
Point p3 = new Point(6, 4);
Point p4 = new Point(2, 4);

Trapezoid trapezoid = new Trapezoid(p1, p2, p3, p4);
```

### Expected Output
```
Area of trapezoid=24.0
```

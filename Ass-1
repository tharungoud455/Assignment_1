class Shape:
    def Area(self):
        pass
    def  Perimeter(self):
        pass
class circle(Shape):
    def  __init__(self,r):
        self.r=r
        self.pi=3.14
    def Area(self):
        
        return f"area of circle :{self.pi*self.r**2}"
    def Perimeter(self):
        return f"perimeter of circle : {2*self.pi*self.r}"
class Triangle(Shape):
    def  __init__(self,b,h):
        self.b=b
        self.h=h
    def Area(self):
        return f"area of Trianle : {0.5*self.b*self.h}"
class  Square(Shape):
    def  __init__(self,side):
        self.side=side
    def  Area(self):
        return f"area of Square : {self.side**2}"
    def  Perimeter(self):
        return f"perimeter of Square {4*self.side}"

#circle

radius=float(input("enter the radius:"))
print(circle(radius).Area())
print(circle(radius).Perimeter())

#triangle

base=float(input("enter the base:"))
height=float(input("enter the height:"))
print(Triangle(base,height).Area())

#square

side=float(input("Enter side length:"))
print(Square(side).Area())
print(Square(side).Perimeter())




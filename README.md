# Python
l = int(input())
b = int(input())
A=l*b #area of rectangle
B=l*l #area of square
print("Area of rectangle:" + str(A))
print("Area of square:" + str(B))
if A==B:
    print("It is square")
else:
    print("It is rectangle")

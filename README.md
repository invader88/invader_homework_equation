# invader_homework_equation
print("Solving of the quadratic equation : ax2 + bx + c = 0")
a = int(input("Enter 'a' value: "))
b = int(input("Enter 'b' value: "))
c = int(input("Enter 'c' value: "))
des = b**2 - 4*a*c
if(des>0):
    print("Descriminant equals to ", des, "so the equation contains ","2 roots")
    root1 = (-b + (b**2 - 4*a*c)**1/2)/2
    root2 = (-b - (b**2 - 4*a*c)**1/2)/2
    print("root1 = ", root1)
    print("root2 = ", root2)
if (des == 0):
    print("Descriminant equals to ", des, "so the equation contains ","1 root")
    root = (-b)/(2*a)
    print("root = ", root)
if (des<0):
    print("Descriminant equals to ", des, "so the equation contains ","no roots")

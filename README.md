- š Hi, Iām @Praveen362
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
Praveen362/Praveen362 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
i am giving code for graphics in python named turtle.
  
  
  
  
 import turtle
colors = ['red', 'purple', 'blue', 'green', 'orange', 'yellow']
t = turtle.Pen()
turtle.bgcolor('black')
for i in range(360):
    t.pencolor(colors[i%6])
    t.width(i//100 + 1)
    t.forward(i)
    t.left(59)

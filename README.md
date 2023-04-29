# final-project-
import turtle
t = turtle.Turtle()

while True:
    weather = input("Enter 'sunny' or 'rainy' or 'snowy':")
    
    if weather == 'sunny':
        location = input("Enter 'beach' or 'mountain' or 'city':")
    if weather == 'sunny' and location == 'beach':
    #sunny - beach
    #sand
        turtle.bgcolor("light blue")
    
        t.up()
        t.goto(-200,200)
        t.down()
        t.color("yellow")
        t.pensize(60)
        t.circle(20)
        
        t.up()
        t.goto(0,-250)
        t.down()
        t.color("AntiqueWhite")
        t.pensize(120)
        t.forward(350)
        t.right(90)
        t.forward(100)
        t.right(90)
        t.forward(300)
        t.right(90)
        t.forward(100)        
   

         #ocean
        t.up()
        t.goto(0,-250)
        t.down()
        t.color("DeepSkyBlue")
        t.left(90)
        t.forward(350)
        t.left(90)
        t.forward(100)
        t.left(90)
        t.forward(350)
        t.left(90)
        t.forward(100)

        t.up()
        t.goto(-200,-300)
        t.down()
        t.left(90)
        t.pensize(60)
        t.color("green")
        t.shape('turtle')
        t.stamp()

        #umbrella
        t.right(90)
        t.up()
        t.goto(200,-150)
        t.down()
        t.color("red")
        t.circle(60,180)
        t.pensize(10)
        t.color('white')
        t.up()
        t.goto(140,-220)
        t.down()
        t.left(180)
        t.forward(80)

        t.hideturtle()
        
    
    #sunny - mountain
    if weather == 'sunny' and location == 'mountain':
        turtle.bgcolor("light blue")
    
        t.up()
        t.goto(-200,200)
        t.down()
        t.color("yellow")
        t.pensize(60)
        t.circle(20)
        
        t.up()
        t.goto(-300,-200)
        t.color('DarkSeaGreen1')
        t.down()
        t.pensize(300)
        t.forward(600)

        t.up()
        t.pensize(3)
        t.goto(-200,-50)
        t.down()
        t.color('CadetBlue4')
        t.begin_fill()
        for i in range (3):
            t.forward(400)
            t.left(120)
        t.end_fill()

        #tree1
        t.up()
        t.goto(-100,-50)
        t.down()
        t.left(50)
        
        t.pensize(10)
        t.color("DarkSlateGray")
        t.begin_fill()
        
        for _ in range (2):
            t.circle(45,90)
            t.circle(45/2,90)
        t.end_fill()

        t.up()
        t.color('brown')
        t.goto(-110,-50)
        t.down()
        t.right(140)
        t.forward(40)

        #tree2
        t.up()
        t.goto(160,-100)
        t.down()
        
        
        t.pensize(10)
        t.color("DarkSlateGray")
        t.left(100)
        t.begin_fill()
        
        for _ in range (2):
            t.circle(45,90)
            t.circle(45/2,90)
        t.end_fill()

        t.up()
        t.color('brown')
        t.goto(160,-85)
        t.down()
        t.right(100)
        t.forward(40)

        #flowers
        for flower in range (5):
            t.up()
            t.goto(-200,-180)
            t.down()
            t.pensize(3)
            t.color("coral2")
            t.left(68)
            t.circle(10)
           
            
        for flower in range (5):
            t.up()
            t.goto(150,-270)
            t.down()
            t.pensize(3)
            t.color("coral2")
            t.left(68)
            t.circle(10)

        for flower in range (5):
            t.up()
            t.goto(0,-100)
            t.down()
            t.pensize(3)
            t.color("coral2")
            t.left(68)
            t.circle(10)
            
##  # sunny - city (cafe) #
        
    if weather == 'sunny' and location == 'city':   
        turtle.bgcolor("light blue")
    
        t.up()
        t.goto(-200,200)
        t.down()
        t.color("yellow")
        t.pensize(60)
        t.circle(20)
        
        t.up()
        t.goto(-350,-300)
        t.down()
        t.pensize(200)
        t.color("black")
        t.forward(700)

        #building1
        t.up()
        t.goto(-300, -205)
        t.down()
        t.left(90)
        t.pensize(10)
        t.color("DarkGray")
        t.begin_fill()
        t.forward(310)
        t.right(90)
        t.forward(100)
        t.right(90)
        t.forward(310)
        t.right(90)
        t.forward(100)
        t.end_fill()
        #building2
        t.up()
        t.goto(-175, -205)
        t.down()
        t.pensize(10)
        t.color("azure3")
        t.begin_fill()
        t.right(90)

        t.forward(280)
        t.right(90)
        t.forward(100)
        t.right(90)
        t.forward(280)
        t.right(90)
        t.forward(100)
        t.end_fill()
        #building3
        t.up()
        t.goto(-60, -205)
        t.down()
        t.pensize(10)
        t.color("cornsilk4")
        t.begin_fill()
        t.right(90)

        t.forward(350)
        t.right(90)
        t.forward(100)
        t.right(90)
        t.forward(350)
        t.right(90)
        t.forward(100)
        t.end_fill()
        #building4
        t.up()
        t.goto(80, -205)
        t.down()
        t.pensize(10)
        t.color("DarkGray")
        t.begin_fill()
        t.right(90)
        
        t.forward(200)
        t.right(90)
        t.forward(100)
        t.right(90)
        t.forward(200)
        t.right(90)
        t.forward(100)
        t.end_fill()
        #building5
        t.up()
        t.goto(20, -210)
        t.down()
        t.pensize(10)
        t.color("azure3")
        t.begin_fill()
        t.right(90)

        t.forward(90)
        t.right(90)
        t.forward(110)
        t.right(90)
        t.forward(90)
        t.right(90)
        t.forward(110)
        t.end_fill()
        #building6
        t.up()
        t.goto(200, -205)
        t.down()
        t.pensize(10)
        t.color("burlywood")
        t.begin_fill()
        t.right(90)

        t.forward(280)
        t.right(90)
        t.forward(100)
        t.right(90)
        t.forward(280)
        t.right(90)
        t.forward(100)
        t.end_fill()
        
        #car1
        t.up()
        t.goto(-286,-290)
        t.down()
        t.color('red')
        
        for _ in range (2):
            t.circle(5,90)
            t.circle(5/2,90)

        t.up()
        t.goto(-260,-280)
        t.down()
        t.right(20)
        t.begin_fill()
        for _ in range (2):
            t.circle(15,90)
            t.circle(15/2,90)
    
        t.up()
        t.goto(-245,-290)
        t.down()
        t.right(20)
        t.end_fill()
        for _ in range (2):
            t.circle(5,90)
            t.circle(5/2,90)
        
        
        
#rainy day
    if weather == 'rainy':
    
        turtle.bgcolor("light grey")
        t.up()
        t.goto(-100,250)
        t.down()
        t.right(20)
        t.color("white")
        t.pensize(60)
        
        for _ in range (2):
        
            t.circle(20,90)
            t.circle(20/2,90)

        t.up()
        t.goto(-50,250)
        t.down()
        t.right(20)

        for _ in range (2):
            t.pensize(70)
            t.circle(50,90)
            t.circle(50/2,90)
    
        t.up()
        t.goto(50,250)
        t.down()
        t.right(20)
    
        for _ in range (2):
        
            t.circle(20,90)
            t.circle(20/2,90)


    #rainy - rain drops
        t.shape("circle")
        t.pensize(40)
        t.color("CadetBlue1")
        t.up()
        t.goto(-200,-70)
        t.down()
        t.stamp()
    
        t.up()
        t.goto(-120,100)
        t.down()
        t.stamp()

        t.up()
        t.goto(-180,60)
        t.down()
        t.stamp()
        
        t.up()
        t.goto(130,70)
        t.down()
        t.stamp()

        t.up()
        t.goto(200,40)
        t.down()
        t.stamp()

        t.up()
        t.goto(120,-30)
        t.down()
        t.stamp()

    #umbrella
        t.up()
        t.goto(50,5)
        t.left(60)
        t.down()
        t.pensize(70)
        t.left(90)
        
        t.color('red')
        t.circle(60,180)

        t.color('black')
        t.pensize(10)
        t.up()
        t.goto(-11,-100)
        t.down()
        t.left(180)
        t.forward(125)

    #ground
        t.up()
        t.goto(-300,-300)
        t.down()
        t.color("ForestGreen")
        t.right(90)
        t.pensize(400)
        t.forward(600)
        
    
#snowy
    if weather == 'snowy':
        turtle.bgcolor("light grey")
        t.up()
        t.goto(-100,250)
        t.down()
        t.right(20)

        t.color("white")
        t.pensize(60)

    
        for _ in range (2):
        
            t.circle(20,90)
            t.circle(20/2,90)

        t.up()
        t.goto(-50,250)
        t.down()
        t.right(20)

        for _ in range (2):
            t.pensize(70)
            t.circle(50,90)
            t.circle(50/2,90)

        t.up()
        t.goto(50,250)
        t.down()
        t.right(20)
        
        for _ in range (2):
            
            t.circle(20,90)
            t.circle(20/2,90)
                

        t.shape("circle")

        t.up()
        t.goto(-200,-100)
        t.down()
        t.stamp()
        
        t.up()
        t.goto(-120,100)
        t.down()
        t.stamp()

        t.up()
        t.goto(-180,40)
        t.down()
        t.stamp()
        
        t.up()
        t.goto(130,70)
        t.down()
        t.stamp()

        t.up()
        t.goto(200,40)
        t.down()
        t.stamp()

        t.up()
        t.goto(120,-30)
        t.down()
        t.stamp()

        
        
        #snowman
        #body
        t.pensize(90)
        t.up()
        t.goto(-100,-100)
        t.down()
        t.begin_fill()
        t.circle(40)
        t.end_fill()
        
        t.up()
        t.goto(-85,-20)
        t.down()
        t.begin_fill()
        t.circle(20)
        t.end_fill()

    
        t.up()
        t.goto(-75,40)
        t.down()
        t.begin_fill()
        t.circle(10)
        t.end_fill()

        #eyes
        t.color("black")
        t.up()
        t.goto(-90,60)
        t.down()
        t.stamp()

        t.up()
        t.goto(-40,60)
        t.down()
        t.stamp()

        #nose
        t.up()
        t.color("orange")
        t.shape("triangle")
        t.goto(-65, 50)
        t.down()
        t.left(50)
        t.stamp()

        #snowman mouth
        for i in range (5):
            t.color('black')
            t.pensize(1)
            t.up()
            t.goto(-80 +(i*7) ,25)
            t.down()
            t.begin_fill()
            t.circle(2)
            t.end_fill()
        #snowmany buttons
        for i in range (3):
            t.up()
            t.goto(-65, -10 - (i*40))
            t.down()
            t.shape("circle")
            t.stamp()
        #arms
        t.up()
        t.goto(-120,-10)
        t.color("brown")
        t.down()
        t.pensize(5)
        t.forward(-50)

        t.up()
        t.goto(-10,-10)
        t.down()
        t.forward(50)

        #snow ground
        t.up()
        t.goto(-300,-300)
        t.down()
        t.color("white")
        t.pensize(300)
        t.left(10)
        t.forward(600)
        
    if weather != 'sunny' or weather != 'rainy' or weather != 'snowy':
        print('try again')
        continue
    else:
        break
        
    
     
    

# IC-2k24-76--RanveerSilawat--cg


import turtle

# Create a graphics window
screen = turtle.Screen()
screen.title("CGM Lab Assignment - Straight Line")
screen.bgcolor("white")

# Create turtle object
pen = turtle.Turtle()

# Set line properties
pen.color("blue")
pen.pensize(4)

# Move to starting point
pen.penup()
pen.goto(-150, 0)

# Draw a straight line
pen.pendown()
pen.goto(150, 0)

# Hide turtle pointer
pen.hideturtle()

# Keep window open
turtle.done()

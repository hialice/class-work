#classwork
x = 0
y = 190
def setup():
    size(640, 480)

def draw():
    global x
    global y
    
    if x >= 590:
        x = 50
    x += 2
   
    background(135, 206, 250)
     
    noStroke()
    fill(0, 255, 0)
    rect(0, height - 100, 640, 100)
    
    fill(255, 255, 0)
    ellipse(640, 0, 200, 200)
    
    fill(255, 255, 255)
    ellipse(x, height/5, 50, 50)
    ellipse(x + 25, height/5, 50, 50)
    ellipse(x - 25, height/5, 50, 50)
    ellipse(x, height/5 - 25, 50, 50)
    
    fill(100)
    triangle(0, height - 100, 0, 100, 150, height - 100) 
    fill(255)
    triangle(0, height - 300, 0, 100, 43, height - 300) 
    
    
    if y <= 100:
        y = 190
    y += -1
    
    fill(255, 100, 0)
    rect(480, height - 200, 100, 100) 
    rect(555, height - 270, 20, 40)
    fill(150, 0, 0)
    triangle(600, 280, 530, 200, 460, 280) 
    rect(515, height - 150, 30, 50)
    fill(225, 200, 0)
    rect(495, height - 185, 20, 20)
    rect(545, height - 185, 20, 20)
    fill(150)
    rect(557, y, 5, 20)
    rect(568, y, 5, 20)
    
    
    fill(0, 170, 0)
    rect(405, height - 120, 5, 20)
    fill(153, 50, 204)
    ellipse(399 + 5/2, height - 120, 10, 10)
    ellipse(398 + 5/2, height - 129, 10, 10)
    ellipse(411 + 5/2, height - 120, 10, 10)
    ellipse(412 + 5/2, height - 129, 10, 10)
    ellipse(405 + 5/2, height - 134, 10, 10)
    fill(225, 225, 0)
    ellipse(405 + 5/2, height - 125, 10, 10)
    
    fill(0, 170, 0)
    rect(430, height - 120, 5, 20)
    fill(255, 20, 147)
    ellipse(424 + 5/2, height - 120, 10, 10)
    ellipse(423 + 5/2, height - 129, 10, 10)
    ellipse(436 + 5/2, height - 120, 10, 10)
    ellipse(437 + 5/2, height - 129, 10, 10)
    ellipse(430 + 5/2, height - 134, 10, 10)
    fill(225, 225, 0)
    ellipse(430 + 5/2, height - 125, 10, 10)
    
    fill(0, 170, 0)
    rect(455, height - 120, 5, 20)
    fill(153, 50, 204)
    ellipse(449 + 5/2, height - 120, 10, 10)
    ellipse(448 + 5/2, height - 129, 10, 10)
    ellipse(461 + 5/2, height - 120, 10, 10)
    ellipse(462 + 5/2, height - 129, 10, 10)
    ellipse(455 + 5/2, height - 134, 10, 10)
    fill(255, 225, 0)
    ellipse(455 + 5/2, height - 125, 10, 10)
    

    fill(165, 69, 19)
    rect(350, height - 200, 25, 100)
    fill(0, 100, 0)
    ellipse(350 + 25/2, height - 230, 40, 40)
    ellipse(350 + 25/2, height - 250, 40, 40)
    ellipse(350 + 25/2, height - 210, 40, 40)
    ellipse(330 + 25/2, height - 240, 40, 40)
    ellipse(330 + 25/2, height - 220, 40, 40)
    ellipse(370 + 25/2, height - 240, 40, 40)
    ellipse(370 + 25/2, height - 220, 40, 40)
    fill(200, 0, 0)
    ellipse(360 + 25/2, height - 230, 20, 20)
    
    fill(165, 69, 19)
    rect(250, height - 200, 25, 100)
    fill(0, 100, 0)
    ellipse(250 + 25/2, height - 230, 40, 40)
    ellipse(250 + 25/2, height - 250, 40, 40)
    ellipse(250 + 25/2, height - 210, 40, 40)
    ellipse(230 + 25/2, height - 240, 40, 40)
    ellipse(230 + 25/2, height - 220, 40, 40)
    ellipse(270 + 25/2, height - 240, 40, 40)
    ellipse(270 + 25/2, height - 220, 40, 40)
    fill(200, 0, 0)
    ellipse(240 + 25/2, height - 240, 20, 20)
    ellipse(260 + 25/2, height - 225, 20, 20)
    
    fill(165, 69, 19)
    rect(150, height - 200, 25, 100)
    fill(0, 100, 0)
    ellipse(150 + 25/2, height - 230, 40, 40)
    ellipse(150 + 25/2, height - 250, 40, 40)
    ellipse(150 + 25/2, height - 210, 40, 40)
    ellipse(130 + 25/2, height - 240, 40, 40)
    ellipse(130 + 25/2, height - 220, 40, 40)
    ellipse(170 + 25/2, height - 240, 40, 40)
    ellipse(170 + 25/2, height - 220, 40, 40)
    fill(200, 0, 0)
    ellipse(140 + 25/2, height - 240, 20, 20)

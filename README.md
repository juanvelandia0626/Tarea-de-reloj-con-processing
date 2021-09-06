# Tarea-de-reloj-con-processing
El codigo desarrollado para el reloj fue

def setup():
    size(1000,500)
    
def draw():
    
    background(321)
    
    m = map(minute(),0,59,0,width)
    s = map(second(),0,59,0,width)
    h = map(hour(),0,23,0,width)
    
    noStroke()
    fill(0, 100, 0)
    circle(h, 360, 120)
    stroke(89)
    
    
    noStroke()
    fill(153, 50, 204)
    circle(m, 220, 100)
    stroke(321)
    
    
    noStroke()
    fill(255, 250, 240)
    circle(s, 90, 70)
    stroke(321)

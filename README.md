# vcxvxvcv
x1 = 0
x2 = 0

def setup():
    size(1880,1000)
    
def draw():
    global x1
    global x2
    ellipse(x1,x2,70,70)
    x1 = x1 + 3
    x2 = x2 + 2

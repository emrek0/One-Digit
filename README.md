# One-Digit

def gun():
    x= int(input("doğum gününü giriniz"))
    while x >= 10:
        x = sum([int(c) for c in str(x)])
    return x

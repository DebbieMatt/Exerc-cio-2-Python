# Exerccio-2-Python

def computepay(a,b):

    if a < 40 :

        return a*b

    else :

        return (40*b + (a - 40)*b*1.5)

hrs = input("Enter Hours worked:")

rt = input('Enter rate per hour: ')

hours = float(hrs)

rate = float(rt)

print('Pay',computepay(hours,rate))

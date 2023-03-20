this is a simple calculator designed in python

while 1:
    def add(n1,n2):
        s=n1+n2
        print(s)
    def mult(n1,n2):
        s=n1*n2
        print(s)
    def sub(n1,n2):
        s=n1-n2
        print(s)
    def div(n1,n2):
        s=n1/n2
        print(s)
    n1=int(input('enter the first num'))
    n2=int(input('enter the second num'))
    c=int(input('1=addition\n 2=multiplication\n 3=sub\n 4=divi\n 5=exit ---'))
    if c==1:
        add(n1,n2)
    elif c==2:
        mult(n1,n2)
    elif c==3:
        sub(n1,n2)
    elif c==4:
        div(n1,n2)
    else:
        exit()# simple-calculator



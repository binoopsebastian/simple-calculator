# simple-calculator
# this is a simple calculator design written in python
f=True
while f==True:
    sum=0
    call=int(input('1: desimal value number\n2: intiger\n'))
    if call == 1:

        call1=float(input('enter the first number\t'))
        call2=float(input('enter the second number\t'))
    elif:
        call1=int(input('enter the first number\t'))
        call2=int(input('enter the second number\t'))
    else:
        print('wrong choice')
        
    print("select a choice : the available options are :\n")
    a=int(input('1 Multiplictaion\n2.Division\n3.Addition\n4.Substraction\n5. exit'))
    if a==1:
        sum+=call1*call2
        print(sum)
    elif a==2:
        sum+=call1/call2
        print(sum)
    elif a==2:
        sum+=call1+call2
        print(sum)
    elif a==4:
        sum+=call1-call2
        print(sum)
    elif a==5:
        break
    else:
        print('wrong choice')

# Fibonacci
def fib(n):
    a=0
    b=1
    while n<1:
        print('Zero or negative values not acceptable')
        break
    if n==1:
            print(a)
    if n>=2:
            print(a)
            print(b)
    for i in range(2,n):
        next=a+b
        a=b
        b=next
        print(b)
# Driver funcion
fib(1) # fib('Enter value of n upto which you want fibonacci number')

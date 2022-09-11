def f():
    print(10)
    f()
f()
def f(c):
    if c==4:
        return
    print(c)
    f(c+1)
f(1)


def f(c):
    if c==0:
        return
    print("yash shukla")
    f(c-1)
f(int(input()))



print name n times

def f(a,c):
    if c==a:
        return
    print("yash shukla")
    f(a+1,c)
f(0,int(input()))



print(1 to n) numbers

def f(a,n):
    if n<a:
        return
    print(a)
    f(a+1,n)
f(1,int(input()))



print(1 to n numbers)normal

def g(n):
    if n<1:
        return
    print(n)
    g(n-1)
g(int(input()))



print(1 to n)backtracking

def f(i,n):
    if i<1:
        return
    f(i-1,n)
    print(i)
n=int(input())
f(n,n)



print(n to 1)backtracking

def f(a,n):
    if a>n:
        return
    f(a+1,n)
    print(a)
f(1,int(input()))



sum of first n numbers parameter method

def sun(a,n):
    if a<1:
        print(n)
        return
    sun(a-1,n+a)
b=int(input())
sun(b,0)



sum of first n numbers by functional method

def sun(n):
    if n==0:
        return 0
    return n+sun(n-1)
f=sun(5)
print(f)



sum of first n numbers parameter method

def sun(a,n):
    if a<1:
        print(n)
        return
    sun(a-1,n+a)
b=int(input())
sun(b,0)



sum of first n numbers by functional method

def sun(n):
    if n==0:
        return 0
    return n+sun(n-1)
f=sun(5)
print(f)




print (1-n) by backtracking

def f(i,n):
    if i<1:
        return
    f(i-1,n)
    print(i)
n=int(input())
f(n,n)




factorial by parameters

def fact(a,b):
    if a==0:
        print(b)
        return
    fact(a-1,b*a)
fact(5,1)




factorial by functional method

def fact(n):
    if n==0:
        return 1
    return n*fact(n-1)
a=fact(6)
print(a)


tell if it's palindrome of not

def f(arr,i):
    if i>len(arr)//2:
        print(True)
        return
    if arr[i]==arr[len(arr)-i-1]:
        f(arr,i+1)
    else:
        print(False)

a=[int(i) for i in input().split()]
f(a,0)

fibonacci sum

def f(n):
    if n<=1:
        return n
    return f(n-1)+f(n-2)

b=int(input())
a=f(b)
print(a)

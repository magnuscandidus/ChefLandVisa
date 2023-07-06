# ChefLandVisa
# cook your dish here
t=int(input())
while t:
    a,x,b,y,c,z=map(int,input().split())
    if(x>=a and y>=b and z<=c):
        print("yes")
    else:
        print("no")
    t-=1

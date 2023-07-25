# car_Reach
# cook your dish here
for i in range(int(input())):
    x,y,k=map(int,input().split())
    if(y%k==0 and x%k==0):
        print("yes")
    else:
        print("no")

# python46-butter-fly-
n= int(input("Enter the number"))
for i in range(n):
    for j in range(n):
        if i==j or i+j==n-1 or j==0 or j==n-1:
            print("*", end=' ')
        else:
            print(" ", end=" ")
    print()

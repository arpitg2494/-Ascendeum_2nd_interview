# PYTHON CODE FOR PATTERN


n = int(input("Enter the number : "))


list_1=["A","B","C","D","E","F","G","H","I","J","K","L","M","N","O","P","Q","R","S","T","U","V","W","X","Y","Z"]

for i in range(n+1):
        for k in range(n-i):
            print(" ",end="")
        for j in range(i):
            print(list_1[j],"",end="")
        print("\n")
for j in range(n):
        for k in range(j+1):
            print(" ",end="")
        for j in range(n-j-1):
            print(list_1[j],"",end="")
        print("\n")





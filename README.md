# Placement-Training
Python 

ARRAY
#Display the smallest element in the array
n=int(input())
a=list(map(int,input().split()))
l=sorted(a)
print(l[0])
#To accept the array and position in which the new element to be inserted from the user and display the array
n=int(input())
a=list(map(int,input().split()))
b=int(input())
c=int(input())
x=a.insert(c-1,b)
print(*a)
#To accept the array elements ,position from the user and delete the element at the given position
n=int(input())
a=list(map(int,input().split()))
position=int(input())
if position<1 or position>n:
    print("Deletion not possible.")
else:
    del a[position-1]
    print(*a)
#To accept the array elements from the user and find the largest element in the array
n=int(input())
arr=list(map(int, input().split()))
largest=max(arr)
print(largest)
#To accept the array from the user and display all the unique elements in the array
n = int(input())
arr = list(map(int, input().split()))
unique = [x for x in arr if arr.count(x) == 1]
if unique:
    print(*unique)
else:
    print("No unique elements in the array")
#Write a program to find the K th smallest element in the array
n = int(input())
k = int(input())
arr = list(map(int, input().split()))
if k > n:
    print("Out of Range")
else:
    arr.sort()
    print(arr[k-1])
#Write a program to Rotate Array n times


    





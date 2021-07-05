import numpy as np
arr = [1, 4, 5, 6, 20,9,12, 8,10]
n = len(arr)
ans=np.sum(arr)

def odd_sum(arr):
    odd = 0
    for i in range(0, n):
        if (i % 2 == 1):
            odd = odd + arr[i]
    return odd

def even_sum(arr):
    even = 0
    for i in range(0, n):
        if (i % 2 == 0):
            even= even + arr[i]
    return even

print(odd_sum(arr))
print(even_sum(arr))
print(odd_sum(arr) + even_sum(arr))
    #sum=sum+ arr[i]
#    print(sum)
#print(sum)
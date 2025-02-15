def icecreamparlour(m, arr):
    n = len(arr)
    for i in range(0, n-1):
        for j in range(i+1, n):
            if arr[i] + arr[j] == m:
                return [i+1, j+1]

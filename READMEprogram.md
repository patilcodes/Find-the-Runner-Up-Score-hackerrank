if __name__ == '__main__':
    n = int(input())
    arr = map(int, input().split())

    newarr=list(arr)
    newarr.sort()
    a=newarr.count(newarr[-1])
    print(newarr[-a-1])
    

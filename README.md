# MinToMax
# cook your dish here
for i in range(int(input())):
    n=int(input())
    a=list(map(int,input().split()))
    print(n-a.count(min(a)))

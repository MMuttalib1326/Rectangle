# Rectangle
You are given four integers a, b, c and d. Determine if there's a rectangle such that the lengths of its sides are a, b, c and d (in any order).

for i in range(int(input())):
    l=list(map(int,input().split()))
    li=sorted(l)
    if((li[0]==li[1]) and (li[2]==li[3])):
        print("YES")
    else:
        print("NO")

# 25-2-2022-2
n=int(input("enter range"))

l=[]

for i in range(n):

    a=int(input("enter elements"))

    l.append(a)

p=[]

n=[]

for i in l:

    if i<0:

        n.append(i)

    else:

        p.append(i)

        

v=[]

for i in p:

    v.append(i)

for i in n:

    v.append(i)

print(v)

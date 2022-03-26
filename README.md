# python
a=[3,4,5,1,2]
b=[1,2,3,4,5]
c=0
d=0
while True:
    e=a[0]
    a.pop(0)
    a.append(e)
    d=len(b)
    c+=1
    if a==b:
        print ('identical')
        break
    if c==d:
        print ('not identical')
        break

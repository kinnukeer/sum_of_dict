# sum_of_dict
#sum of dictionary
#approach-1
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
k=0
for i in d:
  k=k+d[i]+i
print(k)
'''
#approach-2
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
r=d.keys()
s=d.values()
print(sum(r)+sum(s))

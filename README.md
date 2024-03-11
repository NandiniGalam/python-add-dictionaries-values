# python-add-dictionaries-values
#addition of values in dictionary
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v 
res=0 
for i in d:
  res=res+d[i]
  print(res)

#approach 2

d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v 
res=d.values()
print(sum(res))


  

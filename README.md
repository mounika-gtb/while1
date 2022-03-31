# while1
n=int(input())#3 10 5 16 8 4 2 1
hi=n
while n!=1:
   if n%2!=0:
      p=n*3+1
   else:
      p=n//2
   if hi<p:
         hi=p
   n=p
print(hi)

# guessed-problem-statement
# guessing problem
#approach 1
t=int(input())
for _ in range(t):
  
  a,b=input().split()
  r=""
  for i in b:
    if i not in a:
      r=r+i
  print(r)
  '''
  
#approach2
t=int(input())
for _ in range(t):
  a,b=input().split()
  b=int(b)
  r=""
  for i in a:
    x=ord(i)+b 
    if x>=123:
      x=96+(x-122)
      r=r+chr(x)
    else:
      r=r+chr(x)
  print(r)
        

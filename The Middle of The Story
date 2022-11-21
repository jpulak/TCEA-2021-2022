import statistics
n= int(input())
damn=[]
for i in range(n):
  hehe= input()
  ay= hehe.split(" ")
  ugh= tuple(ay)
  if ugh[3]=='MID':
    BRO= list(map(int,ugh[0:3]))
    hehe= statistics.median(BRO)
    damn.append(hehe)
  elif ugh[3]== 'MAX':
    BRO= list(map(int,ugh[0:3]))
    hehe= max(BRO)
    damn.append(hehe)
  elif ugh[3]== 'MIN':
    BRO= list(map(int,ugh[0:3]))
    hehe= min(BRO)
    damn.append(hehe)
  else:
    pass

for i in range(len(damn)):
  print(damn[i])

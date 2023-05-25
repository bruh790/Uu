# print('قـنـاة صـانع الـسـكريبت عبى التيكتوك هي ez.1.7')

 import random
a="azertyuiopqsdfghjklmwxcvbn"
b="AZERTYUIOPQSDFGHJKLMWXCVBN"
n="1234567890"
s="@§%&'(--+/*="
w=8
g=a+b+s+n
x=0
while True:
  pas="".join(random.sample(g,w))
  print("password is: ",pas)
  x+=1
  
  if x==100000000000

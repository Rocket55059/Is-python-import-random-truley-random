import random

count = 0
h = 100

while count < h:
  count += 1
  x = (random.randrange(1, 11)) #this is the number people are trying to guess

  print(x)
  if count == 100:
    break

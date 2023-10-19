# _codsoft-taskno_2
password generator code 
import random
lower = 'abcdefghiklmnopqrstuvwxyz'
upper = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'
symbol = '()[]{}_#%*.-.'
number ='0123456789'

all = lower + upper + symbol + number
length = 10
password = "".join(random.sample(all,length))
print("The generated password is: ", password)

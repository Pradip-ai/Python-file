# Python-file


#exercise from udemy
username = input('what is your username?')
password = input('what is your password?')
password_lenght = len(password)
hidden_password = '*' * password_lenght
print(f'{username}, your password, {hidden_password}, is {password_lenght} letters long')

**amazon_cart = [ #sllicing of the list**
  'notebooks',
  'sunglass',
  'toys',
  'grapes'
]
amazon_cart[0] = 'laptop'
new_cart = amazon_cart
new_cart[2] = 'gum'

print(amazon_cart[0:4])
print(amazon_cart)

**
#Matrix**
matrix =[
  [1, 2, 3],
  [2, 4, 6],
  [7, 8, 9]
]
print(matrix[1] [2])


**#list methods**
basket = [1, 2, 3, 4, 5]
basket.insert(4, 110)

new_list = basket.extend([100, 101])
#print(basket.append(100))
#print(basket)


#Removing

basket.remove(100)
print(basket)

#list methods
basket = ['a', 'b', 'c', 'd']
print(basket.count('b'))

#list methods
basket = ['a', 'b', 'c', 'd', 'b']
print(basket.sort)
print(sorted(basket))

sentence = ' '
new_sentence = ' '.join(['hi ', 'my ', 'name ', 'is ', 'pradip '])
print(new_sentence)

a, b, c, *other = [1, 2, 3, 4, 5, 6] #list unpacking
print(a)
print(b)
print(c)
print(other)

****
#dictionary************
dictionary = {
  'a' : 1,
  'b' : 2
}
print(dictionary['b'])

#dictionary
dictionary = {
  'a' : 1,
  'b' : 2,
  'x' : 3
}
my_list = {
  'a' : 1,
  'b' : 2,
  'y' : 3

}
print(my_list)
print(dictionary)


#dictionary keys
dictionary = {
  123: [1, 2, 3],
  True: 'hello',
  'is magic': True
}
print(dictionary[True])


#tuple 
my_tuple = (1, 2, 3, 4, 5)
print(5 in my_tuple)

#Ternary operator conditional expression 

#condition_if_true if condition else condition _if_else

is_friend = False
can_message = "message allowed" if is_friend else "not allowed to message"
print(can_message)


#short circuting
is_friend = False
is_user = True

if is_friend or  is_user:
  print('best friend forever')
  
  
  #logical operator
print('a'>'A') # This is because on the ASCII (American Standard Code For Information Interchange) CHART the letter "a" equates to 97 (in decimal values) while the letter "b" equates to 98 (in the decimal values)  # 'a' == 97

'b' == 98

'A' == 65

print(not(False))

is_magicain = True
is_expert = False

#check if magician AND expert: "You are a master magician"
if is_expert and is_magicain:
  print("you are a master magician")

elif is_magicain and not  is_expert:
  print(" at least you're getting there")

elif not is_magicain:
  print("you need magic powers")
  
  #for loops, it allows us to line of code over and over. Powerful features of Programming langauge

for item in (1, 2, 3, 4, 5):
 for x in ['a', 'b', 'c']:
   print(item, x)
   print(1, 'c')
   
   #for loops, it allows us to line of code over and over. Powerful features of Programming langaug
   #iterables-> list, dict, tuple., set, string. Iterated -> means one by one in the collection
   
   user = {
  'name': 'golem',
  'age': 5,
  'can_swim': False
}


for item in user.items():
  key, value = item;
  print(key, value)
for item in user.values():
  print(item)

for item in user.keys():
  print(item)



for key, value in user.items():    or k, v
  print(key, value)

#counter

my_list = [1, 2, 3, 4, 5, 6, 7]
counter = 0

for item in my_list:
  counter = counter + item
print(counter)

#enumerete

for i,char in enumerate('1, 2, 3'):
 print(i, char)
 
 for i,char in enumerate(list(range(100))):

 if char == 50:
   print(f'index of 50 is: {i}')
  
  #while loop

#while loop

i = 0
while 50 < 50:
  print(i)
  i += 1
  break
else: # special case, make sure its excuted only the lopp is finisged without the break 
 print('done with all the work')
  
  
  #while loop 2

while True:
  response = input('say somethin: ')
  if (response == 'bye'):
    break
  

#break continue and pass



myList = [1, 2, 3]
for item in myList:
  pass
  print(item)

i = 0
while i < len(myList):
  print(myList)
  i +=1
  pass
  
  #exercise
  picture = [
  [0,0,0,1,0,0,0],
  [0,0,1,1,1,0,0],
  [0,1,1,1,1,1,0],
  [1,1,1,1,1,1,1],
  [0,0,0,1,0,0,0],
  [0,0,0,1,0,0,0]
]

for image in picture:
  for pixel in image:
    if (pixel == 1):
      print('*', end= '')
          
    else:
      print('')
#exercise Find duplicate
some_list = [ 'a', 'b', 'c', 'b', 'd', 'm', 'n', 'n']
duplicate = []
for value in some_list:
  if some_list.count(value) > 1:
    if value not in duplicate:
      duplicate.append(value)
    

print(duplicate)

def sum(num1, num2): #Function can return sth by giving command for return value
  return num1 + num2
print('hi')
print('hello')
print(sum(10, 5))

def sum(num1, num2):
  def another_function(n1, n2):
    return n1 + n2
    return another_function(num1, num2)
    print('hello')
    

total = sum(10, 20)

print(total)

def checkDriverAge(age=20):
  if age == 0: age = input("What is your age?: ")
  while age == '':
   age = input("What is your age?: ")

  if int(age) < 18:
        print("Sorry, you are too young to drive this car. Powering off")
  elif int(age) > 18:
        print("Powering On. Enjoy the ride!");
  elif int(age) == 18:
        print("Congratulations on your first year of driving. Enjoy the ride!")

    

checkDriverAge(18)

def highest_even(li):   # 
  evens = []
  for item in li:
    if item % 2 == 0:
      evens.append(item)
  return max(evens)
  
print(highest_even([10, 2, 6, 8,]))

#walrus operator

a = 'helllllllllllllllloooooo'
if ((n := len(a)) > 10):
  
  
  print(f' too long {n} elements')

while ((n := len(a)) > 1):
  print(n)
  a = a[:-1]
  
  #Scope, sth present in a lot of programming language, what variable do i have acces to?
'''functiona l scope'''

if True:
  x = 10

print(x)

a = 1

def parent():

  
  def confusion():
    return(a)
  return(confusion())
  
print(parent())
print(a)

#start with local 
# parent local 
#global 
#built in python functions

#global keyword
total = 0
def count():
  global total
  total += 1
  return total

count()
count()
print(count())

#object Oriented programming
# working for amazon, delivery drones, code this drone, function, condition logic.If programms becomes large, millions. How can we use OOP to make the code manageable. It is way to make the code eaiser to maintain, write, think, strucuture, extent. For example: Camera, vison another developer 
# Creating your own class

class PlayerCharacter:
  def __int__(self, name):
    self.name = name

  def run(self):
    print('run')
  
player1 = PlayerCharacter()
player2 = PlayerCharacter('Tome')

print(player1)
print(player2)

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
      

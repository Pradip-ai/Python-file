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

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

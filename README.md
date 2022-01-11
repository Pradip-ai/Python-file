# Python-file


#exercise from udemy
username = input('what is your username?')
password = input('what is your password?')
password_lenght = len(password)
hidden_password = '*' * password_lenght
print(f'{username}, your password, {hidden_password}, is {password_lenght} letters long')

amazon_cart = [ #sllicing of the list
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

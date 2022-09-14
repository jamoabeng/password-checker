# password-checker

username = input("What is your username?")
password = input("What is your password?")
pass_length = len(password)
hidden_password = '*' * pass_length
print(f'{username},your password,{hidden_password} is {pass_length} long')

# PIN-and-attemps
I created a program that prompts the user for a pre-set password. If the password is correct, the program stops and records the number of attempts it took. Otherwise, it continues...
attempt=0
while True:
    a=int(input('PIN:'))
    attempt+=1
    if a==4321 and attempt==1:
        print('Correct! It only took you one single attempt!')
        break
    elif a==4321 and attempt!=1:
        print(f'Correct! It took you {attempt} attempts')
        break
    else:
        print('Wrong')
        

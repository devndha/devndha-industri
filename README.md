# devndha-industri
CALCULATOR CLI
#program simple calculator dv as devy
#description:

#program: NI KADEK DEVNDHA ASRI WIDHIANTIKA_F1F02410064
#tgl: 3/30/2025

# process input user
print('Simple Calculator dv')
print('Math Operation') 
print(' 1. Addition       (+)')
print(' 2. Substraction   (-)')
print(' 3. Multiplication (*)')
print(' 4. Division       (/)')

operation = input('Selects Operation (1/2/3/4): ')
number1 = eval(input('Input the First Number: '))
number2 = eval(input('Input the Second Number: '))
number3 = eval(input('Input the Third Number: '))

# the if process
if operation == '1':
    print('User selects the addition operation')
elif operation == '2':
    print('User selects the subtraction operation')
elif operation == '3':
    print('User selects the multiplication operation')
elif operation == '4':
    print('User selects the division operation')
else:
    print('invalid!')

# the process of calculating and displaying the results of operation
if operation == '1':
    result = number1 + number2 + number3
    print(f'result of operation {number1} + {number2} + {number3} = {result}')
elif operation == '2':
    result = number1 - number2 - number3
    print(f'result of operation {number1} - {number2} - {number3} = {result}')
elif operation == '3':
    result = number1 * number2 * number3
    print(f'result of operation {number1} * {number2} * {number3} = {result}')
elif operation == '4':
    result = number1 / number2 / number3
    print(f'result of operation {number1} / {number2} / {number3} = {result}')
else:
    print('invalid!')

# pyteach-tusur-22
#Решения
#Задание 1
name = input('Имя: ')
print('Привет,', name,'!')
#Задание 2
thickness = 5
c = 'K'
for i in range (thickness):
    print((c*i).rjust(thickness-1)+c+(c*i).ljust(thickness-1))
for i in range ((thickness+1)//2):
    print ((c*thickness*5).center(thickness*6))
for i in range (thickness):
     print(((c*(thickness-i-1)).rjust(thickness)+c+(c*(thickness-i-1)).ljust(thickness)).rjust(thickness*6))
#Задание 3
text ='Надеюсь я многому научусь и стану хорошо программировать на Python!'
print(text.title())
Задание 4
amount = 7354,7568
print('{0:,}'.format(6789088))
#Задание 5
height = 15
width = height * 3
for stick_count in range(1, height, 2):
    print(('.=.' * stick_count).center(width, '+'))
print('GOODBYE'.center(width, '^'))
for stick_count in range(height-2, 0, -2):
    print(('.=.' * stick_count).center(width, '+'))

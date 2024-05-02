# Coding-
car_1 = {
   'model' : 'S3',
   'brend' : 'BMW',
   'year' : 2021,
   'price' : 23000
}

car_2 = {
   'model' : 'Nexia-3',
   'brend' : 'Chevrolet',
   'year' : 2016,
   'price' : 16000
}

car_3 = {
    'model' : 'Gentra',
   'brend' : 'Chevrolet',
   'year' : 2016,
   'price' : 17000
}

cars = [car_1, car_2, car_3]

print('     1-mashina')
for k, v in car_1.items():
    print(f'{k}: {v}')
print('\n')
print('     2-mashina')
for k, v in car_2.items():
    print(f'{k}: {v}')
print('\n')
print('     3-mashina')
for k, v in car_3.items():
    print(f'{k}: {v}')

# User details

first_name = input("Hi, what's your name? ")
last_name = input('Nice to meet you ' + first_name + ", what's your family name? ")
print()
print('Thanks fot that, just a few more questions.')
height = int(input('How tall are you (cm) '))
height_mt = height / 100
age = input('How old are you? ')
weight = int(input("What's your weight in kg "))

# List
user_data = [first_name, last_name, str(height_mt), str(age), str(weight)]
user_details = ('Name: ' + user_data[0], 'Surname: ' + user_data[1], 'Height: ' + str(user_data[2]) + 'mt', 'Age: ' +
                str(user_data[3]), 'Weight: ' + str(user_data[4]) + 'kg')
print()
print('Thanks for that. Below your details')
print()
print('\n'.join(user_details))
print()

# Conditional statements
average_men_height = 174
if height > average_men_height:
    print('You are taller than the average man. The average male height worldwide is approximately ' +
          str(average_men_height / 100) + 'mt')
elif height == average_men_height:
    print('You height is in the average range of' + str(average_men_height / 100) + 'mt')
else:
    print('Your are shorter than the average man. The average male height worldwide is approximately ' + str(
        average_men_height / 100) + 'mt')

average_men_weight = 89
if weight > int(average_men_weight):
    print('You weight more than the average man. The average male weight worldwide is approximately ' +
          str(average_men_weight) + 'kg')
elif weight == average_men_weight:
    print('Your weight is in the average range of' + str(average_men_weight) + 'mt.')
else:
    print('Your weight is below the average man weight standard. The average male weight worldwide is approximately ' +
          str(average_men_weight) + 'kg.')

print()
# While loop
weight_difference = weight - average_men_weight
recommended_weight_loss = 2
recommended_weight_gain = 1.5
weight_loss_timeframe = int(weight_difference / recommended_weight_loss)
weight_gain_timeframe = int(weight_difference / recommended_weight_gain)

if weight > int(average_men_weight):
    print('It Seems like you are ' + str(weight_difference) + 'kg overweight.')
    print()
    print('You need to diet for ' + str(weight_loss_timeframe) + ' months.')
else:
    print('It Seems like you are ' + str(-weight_difference) + 'kg underweight.')
    print()
    print('You need to gain ' + str(recommended_weight_gain) + 'kg of muscle a month, for ' +
          str(-weight_gain_timeframe) + ' months.')

month_i = 0

while weight > average_men_weight:
    month_i += 1
    month = 'Month ' + str(month_i) + ': '
    print(month + str(weight-recommended_weight_loss) + 'kg')
    if weight <= average_men_weight:
        break
    weight -= recommended_weight_loss

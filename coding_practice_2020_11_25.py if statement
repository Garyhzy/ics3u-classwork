# coding_practice_2020_11_25.py

#question 1 excerise 34 even or odd
number = int(input("Please insert a number:  "))
mod = number %2
if mod > 0:
  print("It's an odd number")
else: 
  print("It's an even number")

#question 2. excersise 35 Dog years
humanYearsOld = int(input("Please enter the age of a dog in human years: "))

humanYearsOld = 0
	
if humanYearsOld <= 2:
	dogYears = humanYearsOld * 10.5
elif humanYearsOld > 2:
	dogYears = 2 * 10.5
	dogYears += (humanYearsOld-2) * 4

if humanYearsOld == 0:
	print("Please enter a positive integer.")
else:
	print("The dog is {} years old in dog years.".format(dogYears))

#question 3 excersise 36

if letter in "aeiou":
	print("This letter is a vowel.")
else:
	print("This letter is a consonant.")

#question 4 excersise 37

num of sides = int(input("Please enter the number of sides of a shape: "))

if num of sides == 3:
	print("That is a triangle.")
elif num of sides == 4:
	print("That is a square.")
elif num of sides == 5:
	print("That is a pentagon.")
elif num of sides == 6:
	print("That is a hexagon.")
elif num of sides == 7:
	print("The is a heptagon.")
elif num of sides == 8:
	print("That is an octagon.")
elif num of sides == 9:
	print("That is a nonagon.")
elif num of sides == 10:
	print("That is a decagon")
else:
	print("Please enter an integer greater than 2")

#question 5 excersise 38

month = input("Please enter the name of a month: ").lower()

if month == "september" or month == "april" or month == "june" or month == "november":
	print("There are 30 days in this month.")
elif month == "february":
	print("There are 28 or 29 days in this month.")
else:
	print("There are 31 days in this month.")

#question 6 excersise 39

dbLevel = float(input("Please enter a dB level: "))

if dbLevel < 40:
	print("This is extremely quite.")
elif dbLevel > 130:
	print("This is extremely loud.")
	
	
if dbLevel > 40:
	print("This is between a quiet room and an alram clock.")
elif dbLevel > 70:
	print("This is between an alarm clock and a gas lawnmower.")
elif dbLevel > 106:
	print("This is between a gas lawnmower and a jackhammer.")
	
if dbLevel == 40:
	print("This is a quiet room.")
elif dbLevel == 70:
	print("This is an alarm clock.")
elif dbLevel == 106:
	print("This is a gas lawnmower.")
elif dbLevel == 130:
	print("This is a jackhammer.")

#question 7 excersise 40

side 1 = float(input("Please enter the length of first side of a triangle: "))
side 2 = float(input("Please enter the length of the second side of the triangle: "))
side 3 = float(input("Please enter the length of the third side of the triangle: "))

triangleType = ""

if side 1 == side 2 == side 3:
	triangleType = "equalateral"
elif side 1 == side 2 or side 1 == side 3 or side 2 == side 3:
	triangleType = "isoseles"
else:
	triangleType = "scalene"
	
print("That is a {} triangle.".format(triangleType))

#question 8 excersise 41
#I didn't understand this question so I skipped it.....

#question 9 excersise 42
#I didn't understand the frequency thing so I skipped it

#question 10 excersise 43

bank Note Amount = int(input("Please enter a bank note amount: $"))

individual Name = ""

if bank Note Amount == 1:
	individualName = "George Washington"
if bank Note Amount == 2:
	individualName = "Thomas Jefferson"
if bank Note Amount == 5:
	individualName = "Abraham Lincoln"
if bank Note Amount == 10:
	individualName = "Alexander Hamilton"
if bank Note Amount == 20:
	individualName = "Andrew Jackson"
if bank Note Amount == 50:
	individualName = "Ulysses S. Grant"
if bank Note Amount == 100:
	individualName = "Benjamin Franklin"
	
if individual Name == "":
	print("That is not an American bank note in circulation.")
else:
	print("The individual on this bank note is {}.".format(individual Name))


#question 11 excersise 44
month = int(input("Please enter in a month with a numerical value (1-12): "))
date = int(input("Please enter in a date: "))

holiday = ""

if month == 1 or month == 4 or month == 12:
	if month == 1 and date == 1:
		holiday = "New Year's Day"
	elif month == 4 and date == 1:
		holiday = "Canada Day"
	elif month == 12 and date == 25:
		holiday = "Christmas Day"
		
if holiday == "":
	print("That is not a holiday that falls on the same date each year.")
else:
	print("That date is {}.".format(holiday))

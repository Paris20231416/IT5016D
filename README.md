# IT5016D
Repository of IT5016D
Name Xiaoxin Mo
Student ID 20231416

# Square.py
#
# author: A. N. Other
# date: September 2016
 
side_j = int(input("Please enter the length of one side of the square\n\n"))
print("\nThe area of your square is ", side_j ** 2,"\n\n")
 
# Testing
'''
print("My assertions are:"
      "\nj = 5 output = 25"
      "\nj = 12 output = 144")

      is_fuel_in_tank = True
is_driver_licensed = False
is_driver_insured = True
 
print("This program works out whether you can have a car, or a driver....\n")
 

# BooleanOr.py
# Test case assertion 1: result should be True
print("Program output is ",
      is_fuel_in_tank
      or is_driver_licensed
      and is_driver_insured, "\n")
 
print("Removing all the fuel...\n")
is_fuel_in_tank = False
 
# Test case assertion 2: result should be False
print("Program output is now ",
      is_fuel_in_tank
      or is_driver_licensed
      and is_driver_insured, "\n")

# Comments of Boolean Logic
It takes me a quite long time to understand the Boolean Logic in Python.
But it really helps when I tried to understand it as a maths topic.

A=1 
B=0
C=1

A+B=1+0=1
A+C=1+1=1
A*B=1*0=0
A*B=1*1=1


# Number Game (can be divided by 7 but should not be multiples of 5)
list2=[]
for i in range (1000,2000)
  if i%7=0 and i%5!=0
        list2.append(stir(i))
Print(",".join(list2))

# Comments- the useage of !
I found this funny coding online and have a question in here the meaning of usage "!" in coding.
"!" means not in C language


# What day is today (enter an exact day and detemine what day is the date of this year)

time_date=input("please enter the date in format DD/MM/YY)
year,month,day= int(time_date[:4]),int(time_date[4:6]),int(time_date[6:])
month_set=[31,28,31,30,31,30,31,31,30,31,30,31]

if 0 < month < 12 and 0 < day <32
   Print('you enter a right date format)
else:
   Print('please enter a date in format')

if (year % 400 == 0) or (year % 4 == 0) and (year % 100 !=0) and (month > 2):
   d_sum = 1
else: 
   d_sum = 0

i = 0
for i in range(month -1): 

 if i < (month -1):
    d_sum + = month_set[1]
    i+=1

d_sum +=day

print("it's the day"%(year,month,day,d_sum))


# Shut down the computer

import_os_shutdown = input("Do you want to shutdown your computer? enter(yes/no): ") 
if shutdown == 'no': exit() 
else: os.system("shutdown /s /t 1")

# comments: Easy coding but a thinking is whether it is necessary？ Coding should not a barrier for easy life, haha right?

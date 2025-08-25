# love calculator program
print("********** LOVE CALCULATOR **********")
import random
name1=input("enter the your name:")
name2=input("enter the your gf name:")
age=int(input("enter your age:"))
gf_age=int(input("enter ur gf age:"))
age_diff=abs(age-gf_age)
#formatted string
print(f'{name1} loves her gf {name2} and their age difference is {age_diff}' )

# Count trials to get 100
trials = 0
score=0
while score != 100:
    score = random.randint(20, 100)
    trials += 1
score=random.randint(20,100)
print("Your love score is:",score)
if score>90:
    print("you love is stronger and still more stronger")
    print( name2 + " " *3)
    print(("I LOVE YOU\n") * 100)
elif score>70:
    print("ypur love is good")
elif score>50:
    print("not bad but doubt")
elif score==100:
    print("radhe krishna love story")
else:
    print('kasta ide guru')
    print("SORRY!!!! TRY AGAIN UNTIL U GET 100")
print(f"It took {trials} trials to get a love score of 100!")
print("thank you for using love calculator")












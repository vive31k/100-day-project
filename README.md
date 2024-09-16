print('''
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\` . "-._ /_______________|_______
|                   | |o;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/
******************************************************************************     
''')
print("Welcome to treasure island")
print("Your mission is find to treasure")
first1=input("where you want to go??. Left or Right?? ")
if first1=="Right":
    print("Game over you fell in hole filled with traps and died")
elif first1=="Left":
    print("you have come over to lake")
    first2=input("You want to wait for a Boat or you want to Swim ")
    if first2=="Swim":
     print("You are died because shark eat you")
    elif first2=="Boat":
     print("You came across three")
    first3=input("Which color door you want to choose??  Red ,Yellow and Green??")
    if first3=="Red":
     print("Died of hell fire")
    elif first3=="Yellow":
     print("Died of solar beam")
    
    elif first3=="Green":
     print("you won man")
else:
    print("check spellings and capital letter you have put incorrect input")

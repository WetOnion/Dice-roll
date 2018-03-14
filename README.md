# Dice-roll
final version
Dice roll simulator 

 

def rolling_dice_sim(): 

    from random import randint #gives random number 

    roll_again = "y" 

    while roll_again == "y": 

        dice_sides = int(input("between 6 and 30 how many sides on your dice?")) 

        while dice_sides > 30 or dice_sides < 6:  

            dice_sides =int(input("you idiot it has to be between 6 and 30"))#making sure you do the right ammount 

        num_roll = randint (1, dice_sides) 

        print ("your number is",num_roll) 

        roll_again= input("Wanna roll again? y/n")#gives option to continue playing 

         

rolling_dice_sim() 

 

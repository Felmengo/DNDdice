# DNDdice
DND Dice is a program I created for the game Dungeons &amp; Dragons. It contains all the dice types needed for DND.
'''
   
    import random
    import time
    
    sides = ["4","6","8","10","12","20","100"]
    
    
    random.choices(sides)
    
    def cuberoll():
            if changeside == "4":
                    sides = ["1","2","3","4"]
                    print ("the randomness have spoken",random.choice(sides))  
            if changeside == "6":
                    sides = ["1","2","3","4","5","6"]
                    print ("the randomness have spoken",random.choice(sides))    
            if changeside == "8":
                    sides = ["1","2","3","4","5","6","7","8"]
                    print ("the randomness have spoken",random.choice(sides))
            if changeside == "10":
                    sides = ["1","2","3","4","5","6","7","8","9","10"]
                    print ("the randomness have spoken", random.choice(sides))      
            if changeside == "12":
                    sides = ["1","2","3","4","5","6","7","8","9","10","11","12"]
                    print ("the randomness have spoken",random.choice(sides))      
            if changeside == "20":
                    sides = ["1","2","3","4","5","6","7","8","9","10","11","12","13","14","15","16","17","18","19","20"]
                    print ("the randomness have spoken",random.choice(sides)) 
            if changeside == "100":
                    sides = ["10","20","30","40","50","60","70","80","90","100"]
                    print ("the randomness have spoken",random.choice(sides))
            
           
    
    
    print ("--DND dice--")
    changeside = input("Enter the number (4,6,8, 10, 12, 20, or 100 ) of dice you want to roll:")
    
    if changeside not in sides:
            print("Error false input!")
    else:    
            
            if changeside == "4":
                    print("You choose 4 side dice")
                    cuberoll()
            if changeside == "6":
                    print("You choose 6 side dice")
                    cuberoll()
            if changeside == "8":
                    print("You choose 8 side dice")
                    cuberoll()
            if changeside == "10":
                    print("You choose 10 side dice")
                    cuberoll()
            if changeside == "12":
                    print("You choose 12 side dice")
                    cuberoll()
            if changeside == "20":
                    print("You choose 20 side dice")
                    cuberoll()
            if changeside == "100":
                    print("You choose 100 side dice")
                    cuberoll()
        

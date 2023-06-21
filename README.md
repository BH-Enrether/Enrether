from random import randint as enr
from time import sleep

inp = str
ind = str
mybal = 150
s = 3
mh = 1
ak = 0
ab = 0
bb = 0
cb = 0
db = 0
eb= 0
fb = 0
gb= 0
hb= 0
ib= 0
jb = 0
print("")
print("~~~~~~~~~ This Code Is For Hotel Management System ~~~~~~~~~ ")
print(""*3)
while True: 
    
    
    while True:
        try:
            while True:
                print("")
                sleep(0.9999)
                print("~ Home Page")
                print("")
                print("1. Order Menu")
                print("2. My Balance")
                print("3. Earn Money")
                print("4. Store")
                print("5. Help")
                print("6. Exit")
                print(''*2)
                print("Note: Always Input The Correct Index.")
                print("")
                inp = input("~ Enter Your Index: ")
                if inp == "1":
                    sleep(0.21)
                    print(""*2)

                    
                    
                    while s==3:
                        print("Input 0 to Exit")
                        print("")
                        print("1. Pizza     -   $50")
                        print("2. Hot Dog   -   $45")
                        print("3. Fries     -   $30")
                        print("4. Momos     -   $20")
                        print("5. Toffee    -   $1")
                        print("6. Chocolate -   $5")
                        print("7. Sandwich  -   $25")
                        print("8. Juice     -   $10")
                        print("9. Burger    -   $9")
                        print("10. Noodles  -   $50")
                        print(""*2)
                        sleep(0.65)
                        print("")
                        print("Note: Always Input The Correct Index.")
                        print("")
                        
                        ind = input("~ Enter Index TO Buy An Item or '0' to Back: ")
                        print("")
                        if ind == "0":
                            s = s + 1
                        if ind == "1":
                            print("")
                            if mybal>=50:
                                print(""*2) 
                                print("~ Purchasing Pizza...")
                                sleep(2)
                                print("")
                                print('~ Sucessfully Purchased Pizza. ')
                                mybal=mybal-50
                                ab+=1
                                print(""*2)
                            else:
                                print("")
                                print("~ Not Sufficient Money!")
                                print(f"~ Your Balance is ${mybal}")
                                sleep(1.5)
                                print("")
                        if ind == "2":
                            print("")
                            if mybal>=45:
                                print(""*2) 
                                print("~ Purchasing Hot Dog...")
                                sleep(2)
                                print("")
                                print('~ Sucessfully Purchased Hog Dof. ')
                                mybal=mybal-45
                                bb+=1
                                print(""*2)
                            else:
                                print("")
                                print("~ Not Sufficient Money!")
                                print(f"~ Your Balance is ${mybal}")
                                sleep(1.5)
                                print("")
                        if ind == "3":
                            print("")
                            if mybal>=30:
                                print(""*2) 
                                print("~ Purchasing Fries...")
                                sleep(2)
                                print("")
                                print('~ Sucessfully Purchased Fries. ')
                                mybal=mybal-30
                                cb+=1
                                print(""*2)
                            else:
                                print("")
                                print("~ Not Sufficient Money!")
                                print(f"~ Your Balance is ${mybal}")
                                sleep(1.5)
                            
                                print("")
                        if ind == "4":
                            print("")
                            if mybal>=20:
                                print(""*2) 
                                print("~ Purchasing Momos...")
                                sleep(2)
                                print("")
                                print('~ Sucessfully Purchased Momos. ')
                                mybal=mybal-20
                                db+=1
                                print(""*2)
                            else:
                                print("")
                                print("~ Not Sufficient Money!")
                                print(f"~ Your Balance is ${mybal}")
                                sleep(1.5)
                                print("")
                        if ind == "5":
                            print("")
                            if mybal>=1:
                                print(""*2) 
                                print("~ Purchasing Toffee...")
                                sleep(2)
                                print("")
                                print('~ Sucessfully Purchased Toffee. ')
                                mybal=mybal-1
                                eb+=1
                                print(""*2)
                            else:
                                print("")
                                print("~ Not Sufficient Money!")
                                print(f"~ Your Balance is ${mybal}")
                                print("")
                                sleep(1.5)
                        if ind == "6":
                            print("")
                            if mybal>=5:
                                print(""*2) 
                                print("~ Purchasing Chocolate...")
                                sleep(2)
                                print("")
                                print('~ Sucessfully Purchased Chocolate. ')
                                mybal=mybal-5
                                fb+=1
                                print(""*2)
                            else:
                                print("")
                                print("~ Not Sufficient Money!")
                                print(f"~ Your Balance is ${mybal}")
                                sleep(1.5)
                                print("")
                        if ind == "7":
                            print("")
                            if mybal>=25:
                                print(""*2) 
                                print("~ Purchasing Sandwich...")
                                sleep(2)
                                print("")
                                print('~ Sucessfully Purchased Sandwich. ')
                                mybal=mybal-25
                                gb+=1
                                print(""*2)
                            else:
                                print("")
                                print("~ Not Sufficient Money!")
                                print(f"~ Your Balance is ${mybal}")
                                sleep(1.5)
                                print("")
                        if ind == "8":
                            print("")
                            if mybal>=10:
                                print(""*2) 
                                print("~ Purchasing Juice...")
                                sleep(2)
                                print("")
                                print('~ Sucessfully Purchased Juice. ')
                                mybal=mybal-10
                                hb+=1
                                print(""*2)
                            else:
                                print("")
                                print("~ Not Sufficient Money!")
                                print(f"~ Your Balance is ${mybal}")
                                sleep(1.5)
                                print("")
                        if ind == "9":
                            print("")
                            if mybal>=9:
                                print(""*2) 
                                print("~ Purchasing Burger...")
                                sleep(2)
                                print("")
                                print('~ Sucessfully Purchased Burger. ')
                                mybal=mybal-9
                                ib+=1
                                print(""*2)
                            else:
                                print("")
                                print("~ Not Sufficient Money!")
                                print(f"~ Your Balance is ${mybal}")
                                sleep(1.5)
                                print("")
                        if ind == "10":
                            print("")
                            if mybal>=50:
                                print(""*2) 
                                print("~ Purchasing Noodles...")
                                sleep(2)
                                print("")
                                print('~ Sucessfully Purchased Noodles. ')
                                mybal=mybal-50
                                jb+=1
                                print(""*2)
                            else:
                                print("")
                                print("~ Not Sufficient Money!")
                                print(f"~ Your Balance is ${mybal}")
                                sleep(1.5)
                                print("")
                        
                                
                        
                elif inp=="2":
                    print("")
                    print(f"~ Your Current Balance is ${mybal}")
                    print("")
                    sleep(2)
                elif inp=="6":
                    print(""*2)
                    print('~ Wait For Closing...')
                    sleep(1.2)
                    exit()
                elif inp == "3":
                    sleep(1.5)
                    print("")
                    print("~Here You Can Earn Money By Playing Game")
                    print("")
                    print("Input 'exit' to back")
                    print("")
                    while mh==1:
                        rngn = enr(0,100)
                        x = enr(0,50)
                        y = enr(0,50)
                        c = int(x-y)
                        d = int(x + y)
                        
                        if rngn <=25:
                            print(f"{x} + {y} = ")
                            iss = input("Ans: ")
                            if iss == "exit":
                                mh = mh + 1
                               
                            elif int(iss) == d:
                                sleep(1)
                                print("")
                                print("~ Correct, You Have Received $30")
                                mybal+=30
                                print("")
                            else: 
                                print("")
                                print("Wrong Answer!")
                                sleep(0.555)
                                print("")
                        elif rngn <=50 and rngn >25:
                            print(f"Question. {x} - {y}  ")
                            
                            iw = input("Ans: ")
                            if iw == "exit":
                                mh = mh + 1
                                
                            elif int(iw) == c:
                                sleep(1)
                                print("")
                                print("~ Correct, You Have Received $30")
                                mybal+=30
                                print("")
                            else: 
                                print("")
                                print("Wrong Answer!")
                                sleep(0.555)
                                print("")
                elif inp=="4":
                    print('')
                    print('Processing...')
                    print('')
                    sleep(1)

                    print(f'Pizza: {ab}')
                    print(f'Hot Dog: {bb}')
                    print(f'Fries: {cb}')
                    print(f'Momos: {db}')
                    print(f'Toffee: {eb}')
                    print(f'Chocolate: {fb}')
                    print(f'Sandwich: {gb}')
                    print(f'Juice: {hb}')
                    print(f'Burger: {ib}')
                    print(f'Noodles: {jb}')
                    print(""*2)
                    sleep(0.99)
                elif inp=="5":
                    print("")
                    sleep(0.99)
                    print("-----Help Box-----")
                    print("")
                    sleep(0.22)
                    xc =''' ~ This Code Is A Hytothetical Situation Of A Hotel Managament System In Which A User Can Buy Food Items By Virtual Money And Also That Money Can Be Earned By Playing Simple Mathematical Games And You Can 
Also Check Your Store That which Items You Have Purchased. You Can Also Check Your Balance In The Home 
Page By Inputting '2'. Hope You May Find A Smile By Using This.'''
                    print(xc)
                    print(""*2)
                    print("Code By: Enrether")
                    print("Instagram: @enrether")
                    print("Snapchat: @enrether_007")
                    print("Telegram: @enrether")


                else: 
                    print("")
                    print("~ Please Input The Right Index.")
                    print("")
        except ValueError:
            print('An Error Occurred!')
    


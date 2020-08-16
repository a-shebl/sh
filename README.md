# project 1
Dice Roller
from numpy import *

while True:
    print("this is a dice roller simulator")
    x = input("press y to roll again")
    while x=="y":


        print("[==========]")
        print( "[          ]")
        print( "[          ]")
        for x in random.randint(0,7,1):
            if x==1:
                print("     0 ")
            elif x==2:
                print("    0  0")
            elif x==3:
                print("     0\n"
                      "     0\n"
                      "     0")
            elif x==4:
                print("   0   0\n"
                      "   0   0")
            elif x==5:
                print("   0   0\n"
                      "     0\n"
                      "   0   0")
            else:
                print("    0 0 0\n"
                      "    0 0 0")

        print( "[          ]")
        print( "[          ]")
        print("[==========]")






#!/usr/bin/python

import random

roll = random.randint(2,12)
play = ''

while play != 'no':
        if roll == 7 or roll == 11:
                print "Roll of: ", roll
                play = raw_input("You win. Play again (yes/no)?\n")
                roll = random.randint(2,12)
        elif roll == 2 or roll == 3 or roll == 12:
                print "Roll of: ", roll
                play = raw_input("You loose. Play again (yes/no)?\n")
                roll = random.randint(2,12)
        else:
                print "Roll of: ", roll
                print "Point is now: ", roll
                roll2 = random.randint(2,12)
                while roll2 != roll:
                        print "**Roll of: ", roll2
                        if roll2 == 7:
                                play = raw_input("You loose. Play again (yes/no)?\n")
                                break
                        roll2 = random.randint(2,12)
                if play == 'no':
                        break
                print "Roll of: ", roll2
                play = raw_input("You win. Play again (yes/no)?\n")
                roll = random.randint(2,12)

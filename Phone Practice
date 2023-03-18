#Sehajveer Dhillon
#Phone Practice
def chart():
    print("     Phone Letter Conversion")
    print()
    print("     Q         ABC       DEF")
    print("     1          2         3")
    print()
    print("    GHI        JKL       MNO")
    print("     4          5         6")
    print()
    print("    PRS        TUV       WXY")
    print("     7          8         9")
    print()
    print("                Z")
    print("                0")
    print()
    
def convert(let):
    if let == "q":
        num = 1
    elif let == "a" or let == "b" or let == "c":
        num = 2
    elif let == "d" or let == "e" or let == "f":
        num = 3
    elif let == "g" or let == "h" or let == "i":
        num = 4
    elif let == "j" or let == "k" or let == "l":
        num = 5
    elif let == "m" or let == "n" or let == "o":
        num = 6
    elif let == "p" or let == "r" or let == "s":
        num = 7
    elif let == "t" or let == "u" or let == "v":
        num = 8
    elif let == "w" or let == "x" or let == "y":
        num = 9
    elif let == "z":
        num = 0
    return num
alpha = []
numerical = [] 
chart ()
letter = input ("Enter a letter: ")
while letter.isalpha() == False or len(letter) != 1:
    letter = input ("Invalid input. Enter a letter: ")
while letter != "0":
    alpha.append(letter)
    num = convert(letter)
    numerical.append(num)
    print ("Your letter",letter,"converts to",num)
    letter = input ("Enter a letter (type 0 to quit): ")
    while (letter.isalpha() == False or len(letter) != 1) and letter != "0":
        letter = input ("Invalid input. Enter a letter: ")
print ()
print ("All os your letters",alpha)
print ("Convert to",numerical)

# Party-Python
#A very basic basic game build 
#work in progress

name = input('Hello, my name is Jay Bizzle.  What is your name: ').strip()

quest_1 = input("Alright {}! Shall we play a game? ".format(name))

if quest_1 == ("yes") or ("yes"):
    print("Word. Lets do this thing!")
elif quest_1 == ("no") or ("No"):
    print("later days")

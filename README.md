# Mad-Libs

""" Mad Libs Generator
----------------------------------------
"""

loop = 1
while (loop < 10):

    number = input("Choose a number between 10 and 99: ")
    noun = input("Choose a noun: ")
    noun1 = input("Choose a type of transportation: ")
    noun2 = input("Choose a plural noun: ")
    adjective = input("Choose an adjective: ")
    adjective1 = input("Choose an adjective: ")
    noun4 = input("Choose a noun: ")
    food = input("Type of food (plural): ")
    silly = input("Write a silly word: ")
    noun5 = input("Choose a noun: ")
    verb = input("Choose a verb (past tense): ")
    verb1 = input("Choose a verb: ")
    noun6 = input("Choose a noun: ")
    verb2 = input("Choose a verb (past tense): ")
    body = input("Name a body part: ")
    exclamation = input("Write an exclamation: ")
    icky = input("something icky: ")
    noun7 = input("Choose a name of a planet in our solar system: ")

    print ("------------------------------------------")
    print ("Welcome to the year 70",number,". It was my first day as Intergalactic Space Sheriff,")
    print ("so I decided to patrol planet ",noun,".")
    print ("I jumped into my space ",noun1," turned on the antigravity ",noun2,",")
    print ("And traveled at ",adjective,"speed towards the newly found planet at the edge of our solar system.")
    print ()
    print ("When I stepped onto the",adjective1,"surface, I came face-to-face with an alien.")
    print ("He was the size of a",noun4,"and looked like a giant lump of",food,".")
    print ()
    print (silly," I said to him, the galactic word for “hello.”")
    print ("But the alien didn't respond.")
    print ("Instead he pulled out his laser ",noun5, ",",verb," it at my direction, then tried to ",verb1," me.")
    print ("Quickly I activated my super cool defense ",noun6,".")
    print ("The laser beam ",verb2," off it and hit the alien on the ",body,".")
    print ("“",exclamation, "!” yelled the alien as he turned into a big puddle of ",icky,".") 
    print ("Exhausted, I teleported back to the space station near ",noun7,"." )
    print ("This job is going to be tougher than I thought.")
    print ("------------------------------------------")

    loop = loop + 1

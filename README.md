# Final-Project---SuperHero-Story
# Aidan Morgan - Spring 2021
#The Adventures of ___: Earth's Okayest Hero
# Youtube Link
# https://www.youtube.com/watch?v=Od5cfc6rUVo

import time

print("Welcome to your own personal Superhero Story!")

name = input("Enter Your Name: ")

print("The Adventures of",name,": Earth's Okayest Hero")

print("Here, you will discover your powers in your very first adventure.")
time.sleep(1)
print("But be careful, every choice and decision matters and affects the outcome")
time.sleep(1)
occupation = input("Enter your occupation:")

print("Part I: Just a Normal Day")
print("\n")
print("You go through your boring, every day shift with your job as a(n)",occupation)
time.sleep(1)
print("All of a sudden you notice something in the distance \nheading straight towards you")
time.sleep(1)
print("As it gets closer, you realize it is a...a...")
print(".....")
time.sleep(1)
print(name, ": What the hell is that.....")
time.sleep(3)
print("A METEOR!!!")
time.sleep(1)
print("The meteor strikes you head on as you crumble into the destruction")
time.sleep(2)
superpower = input("a) Does the meteor give you your superpower? \nb) Or nah that's lame we want a better way? \n ")

##IF player decides meteor causes powers
print("\n")
print("Part II: A Hero is Born")
if superpower.lower().strip() == 'a':
    print("You somehow survived the meteor strike with minor injuries.")
    time.sleep(1)
    print("You feel fine at first, but then your body starts aching.")
    time.sleep(1)
    print("You sprint home faster than ever before as you feel your body changing.")
    time.sleep(1)
    print("You get home only to feel yourself grow stronger.")
    print("You get to the bathroom and look at your reflection....")
    time.sleep(1)
    print("only to find your skin glowing!")
    time.sleep(1)
    print(name,": What, What's happening to me!?")
    time.sleep(1)
    print("\n")

#Funny Joke Alert!

if superpower.lower().strip() == 'b':
    print("\n")
    time.sleep(1)
    print("Sorry, the plot demands that you gain your powers from the meteor. \nWe didn't have enough budget to give you an alternate choice")
    print("You somehow survived the meteor strike with minor injuries.")
    time.sleep(1)
    print("You feel fine at first, but then your body starts aching.")
    time.sleep(1)
    print("You sprint home faster than ever before as you feel your body changing.")
    time.sleep(1)
    print("You get home only to feel yourself grow stronger.")
    print("You get to the bathroom and look at your reflection....")
    time.sleep(1)
    print("only to find your skin glowing!")
    time.sleep(1)
    print(name,": What, What's happening to me!?")
    time.sleep(1)
    print("\n")





##Fire Power
print("What should your newly acquired power be: ")
time.sleep(1)
power = input("a) The ability to incinerate and use fire as a main source of power.\nb) Super Strength.\nc) Use of magical abilities such as telekinesis and more wizard-like spells\n")

if power.lower().strip() == 'a':
    print("\n")
    print("Your body combusts into flames as you struggle to keep your sanity and calm.")
    time.sleep(1)
    print(name,": AHHHHHHHHH")
    time.sleep(1)
    print("You jump into the shower and put out the flames \nonly to burst right back into flames")
    time.sleep(1)
    print("Finally, it is over as you control your new powers, but now, you need a suit.")
    time.sleep(1)
    print("After gathering flame-retardant materials, you build your very own suit!")
    time.sleep(1)
    print(name,": This oughta work.")
    time.sleep(1)
    print("Just then, you hear the news broadcast.")
    time.sleep(2)
    print("\n")
    print("Anchorman: 'Citizens of New York, be alert! \nThere has been a jail break and there are villains on the loose!")
    print("You put on your suit and head straight outside to save the city!")
    time.sleep(2)

#Fire Combat
    print("\n")
    print("As you get outside, you see multiple villains wreaking havoc.")
    print("You see Spider-Man villain, SandMan terrorizing civilians.")
    time.sleep(1)
    print(name, ": I gotta do something!")
    time.sleep(1)
    print(name, ": Aw man what should I do!")
    time.sleep

    attack = input("a) Throw a Fireball at him \nb) Charge up and hit him with a fire punch\n")
    if attack.lower().strip() == 'a':
        print("\n")
        print(name, ":Take this SandMan!")
        time.sleep(2)
        print("*Your fireball throw missed by 20 feet")
        time.sleep(1)
        print("You throw another fireball, this time landing a shot!")
        print("This causes SandMan to flee as citizens are saved.")

    elif attack.lower().strip() == 'b':
        print("\n")
        print("You heat up and sprint towards the SandMan.")
        time.sleep(1)
        print(name, ": Here goes nothing!")
        time.sleep(1)
        print("*You charge up and hit SandMan with a flaming uppercut")
        print("He disinegrates into sand and floats away in the air.")
        time.sleep(1)
        print("\n")

# The Avengers Meeting
    print("Part III: Oh Hey, It's the Avengers Now")
    print("Spider-man: Hey you! Good work out there, but what is your name?")
    print("\n")
    Heroname = input("What would you like your superhero name to be:")
    print("\n")
    print(name,": My name is",name,",but you can call me",Heroname)
    print("\n")
    print("Spider-man: Well",Heroname,"come with me, we got some work to do.")
    time.sleep(1)
    print("*You and Spider-man go to the center of town \nwhere multiple villains are wreaking havoc.")
    time.sleep(1)
    print("You arrive to see many heroes in the fight, including \nIron Man, Scarlet Witch, The Hulk, and Thor.")
    time.sleep(1)
    print("\n")
    print("Iron Man: Peter, who is this?")
    time.sleep(1)
    print("Spider-man: This is",name,"but they also go as",Heroname)
    time.sleep(1)
    print("Well kid, I hope you're ready for the fight of your life.")



#The Final Battle - Fire
    print("\n")
    print("Part IV: The Final Battle")
    time.sleep(1)
    print("\n")
    print("Thor: Alright kid, time to go to work.")
    time.sleep(1)
    print(Heroname,": I'm ready to save New York City!")
    time.sleep(1)
    print("Scarlet Witch: That's just what we need, why don't you come with me and Hulk")
    time.sleep(1)
    print("Hulk: SMASH!!")
    time.sleep(1)
    print("\n")
    print("*Scarlet Witch, Hulk, and you head towards the northern section of town \n you end up running into Ultron, Dr. Doom, and Venom!")
    print("Scarlet Witch: I want Ultron, this is personal to me.")
    time.sleep(1)
    print("Hulk: HULK SMASH DOOM")
    time.sleep(1)
    print(Heroname,": Well, I guess I got Venom for myself.")
    time.sleep(1)
    print("\n")
    print("Venom: Fresh meat up for the taking, this'll be easy!")
    time.sleep(1)
    print("It's time to fight your first ever bad guy!")
    time.sleep(1)
    print("\n")
    print(Heroname,": Alright Venom, time for you to die!")
    print("Venom goes towards you and lands a clean swipe, cutting your face.")
    time.sleep(1)
    print("\n")
    print("What should you do to attack venom!")
    time.sleep(1)
    venom = input("A) Combust into flames and charge into Venom\nB) Shoot multiple fireballs towards Venom in hopes that he combusts. \n")
    time.sleep(1)
    print("\n")
    if venom.lower().strip() == 'a':
        print("You charge up and combust into a flaming body.")
        time.sleep(1)
        print("Venom falls back and tries to put out the flames covering his body.")
        time.sleep(1)
        print("Venom: You think that can stop me!")
        time.sleep(1)
        print("Venom comes back and tries to put an end to your life.")
        print("You dodge his attack and strike a flame right at the center of his back. \nHe falls and doesn't get back up with a hole in his back.")
    elif venom.lower().strip() == 'b':
        print("You start hurling fireballs towards Venom in order to take him down.")
        time.sleep(1)
        print("Multiple shots land as he begins to go up in flames.")
        print("You keep firing and it becomes to much for Venom to handle so he burns to the ground in ashes")
        time.sleep(1)
        print(Heroname,": Not so bad for my first fight huh.")
    else:
        pass

    # The Decision - Fire
    print("\n")
    time.sleep(1)
    print("Part V: The Decision")
    print("You regroup yourself after your fight and go to help your new allies.")
    time.sleep(1)
    print("You notice both of your allies struggling to defeat their enemies.")
    time.sleep(1)
    print("\n")
    print("Scarlet Witch:",Heroname,"I need your help!")
    print("Hulk: HULK NEED HELP!!")
    time.sleep(1)
    print("There may be time to help both of your allies, \nbut you may only be able to save one.")
    time.sleep(1)
    print("\n")
    savior = input("A) Save Hulk \nB)Save Scarlet Witch \n")

    #Save Hulk - Fire
    if savior.lower().strip() == 'a':
        print("\n")
        print(Heroname, ": I'm coming Hulk!")
        time.sleep(1)
        print("You send fireballs towards Doom and save Hulk as Doom disinegrates")
        time.sleep(1)
        print("However, you turn around to see Ultron strike a laser through Scarlet Witch's chest")
        time.sleep(1)
        print("She drops to the ground, lifeless, while you stand there in shock.")
        time.sleep(1)
        print(Heroname,": This, this is my fault.")
        print("Hulk: We must go")
        time.sleep(1)
        print("\n")
        print("You and Hulk regroup with Spider-man, Iron Man, and Thor")
        time.sleep(1)
        print("Iron Man: Where is Wanda?")
        time.sleep(1)
        print(Heroname,": I...I..could not save them both.")
        print("Iron Man: Jesus kid, it's not your fault.")
        print("Thor: You did everything you could have.")
        time.sleep(1)
        print("With Doom and Venom gone, there's 2 less villains to worry about.")
        print("What comes next though?")
        time.sleep(1)
        print("Spider-man: We gotta finish this fight!")
        print("Thor: You're right, let's end this once and for all.")

    # Save Wanda - Fire
    if savior.lower().strip() == 'b':
        print("\n")
        print(Heroname, ": I'm coming Scarlet Witch!")
        time.sleep(1)
        print("You send fireballs towards Ultron and save Wanda as you cause Ultron to malfunction")
        time.sleep(1)
        print("However, you turn around to see Doom stomp on Hulk's face, ending his life.")
        time.sleep(1)
        print("His body lays there, lifeless, while you stand there in shock.")
        time.sleep(1)
        print(Heroname,": This, this is my fault.")
        print("Scarlet Witch: We must go")
        time.sleep(1)
        print("\n")
        print("You and Wanda regroup with Spider-man, Iron Man, and Thor")
        time.sleep(1)
        print("Spider-man: Where is Hulk?")
        time.sleep(1)
        print(Heroname,": I...I..could not save them both.")
        print("Iron Man: Jesus kid, it's not your fault.")
        print("Thor: You did everything you could have.")
        time.sleep(1)
        print("With Ultron and Venom gone, there's 2 less villains to worry about.")
        print("What comes next though?")
        time.sleep(1)
        print("Spider-man: We gotta finish this fight!")
        print("Thor: You're right, let's end this once and for all.")
    else:
        pass

    ## The End? - Fire
    print("\n")
    time.sleep(1)
    print("Part VI: The End?")
    time.sleep(1)
    print("Iron Man: Alright guys let's end this once and for all.")
    time.sleep(1)
    print("\n")
    print("Green Goblin: Not so fast Iron Man!")
    time.sleep(1)
    print("Green Goblin: Did you think this would be easy?")
    time.sleep(1)
    print("Iron Man: You're going down Goblin!")
    time.sleep(1)
    print("Green Goblin: You may have defeated me last time, but this time will be different!")
    time.sleep(1)
    print("Thor: Time to go to battle, you ready",Heroname)
    print("Green Goblin: Now hold on! Why don't you come fight with us",Heroname)
    time.sleep(1)
    print("Green Goblin wants you to join them, but you wouldn't turn bad, Would you?")
    print("\n")
    evil = input("A) Join the Villains \nB) Stay on the side of Good \n")

    #Evil Ending - Fire
    if evil.lower().strip() == 'a':
        print("\n")
        time.sleep(1)
        print(Heroname,": Time to fulfill my destiny, I'm on your side Goblin.")
        time.sleep(1)
        print("Green Goblin: That's my boy!")
        time.sleep(1)
        print("Iron Man: You'll really just betray us like that kid!")
        print("Thor: Guess we'll just have to kill you too!")
        time.sleep(1)
        print("\n")
        print("You, Green Goblin, and the freed villains take on the remaining avengers. \nOne by one you are able to take down the remaining avengers, \nputting an end to the heroes in New York.")
        time.sleep(1)
        print("Green Goblin: Great Job,",Heroname,"time to take this city over!")
        time.sleep(1)
        print("You and the villains destroy NYC and take over, \nforcing innocent civilians to obey your every rule")
        time.sleep(1)
        print("The Avengers were no more, and you lived the rest of your life with power.")
        time.sleep(1)
        print("\n")
        print("The End.")

    #Hero Ending - Fire
    if evil.lower().strip() == 'b':
        print("\n")
        time.sleep(1)
        print(Heroname, ": I'd never join someone with the likes of you Goblin!")
        time.sleep(1)
        print("Green Goblin: Suit Yourself.....Kill Them All!!")
        time.sleep(1)
        print("Avengers: Alright team, let's end this!")
        time.sleep(1)
        print("\n")
        print("You and the remaining Avengers go against the rest of the villains. \nOne by one you defeat and stop villain after villain.")
        time.sleep(1)
        print("After locking up the rest of the villains, you and the Avengers have successfully saved the day.")
        print("Iron Man: Not too bad kid, I think we have a spot for you on the team.")
        time.sleep(1)
        print(Heroname, ": You...you mean it?")
        time.sleep(1)
        print("Iron Man: Ah what the hell, your an Avenger now!")
        time.sleep(1)
        print("\n")
        print("You are now officially an Avenger, and you vowed to save the city until the death of you.")
        time.sleep(1)
        print("\n")
        print("The End.")

    ##Strength Story
            
    elif power.lower().strip() == 'b':
        print("\n")
        print("You feel yourself growing stronger as you get bigger in size.")
        print(name,": How is this possible?")
        time.sleep(1)
        print("As you grip onto the sink, your strength causes you to snap it in half!")
        time.sleep(1)
        print(name,": Woah! That was pretty cool.")
        print("\n")
        time.sleep(1)
        print("Just then, you hear the news broadcast.")
        time.sleep(2)
        print("\n")
        print("Anchorman: 'Citizens of New York, be alert! \nThere has been a jail break and there are villains on the loose!")
        print("You put on some fresh clothes and head straight outside to save the city!")


        #Strength Combat
        print("\n")
        print("As you get outside, you see multiple villains wreaking havoc.")
        print("You see Spider-Man villain, SandMan terrorizing civilians.")
        time.sleep(1)
        print(name, ": I gotta do something!")
        time.sleep(1)
        print(name, ": Aw man what should I do!")
        time.sleep(1)
    attack2 = input("a) Throw a car at him \nb) Charge up and hit him with a mean uppercut\n")
    if attack2.lower().strip() == 'a':
        print("\n")
        print(name, ":Take this SandMan!")
        time.sleep(2)
        print("*Your car throw missed by 20 feet")
        time.sleep(1)
        print("You throw another car, this time landing a shot!")
        print("This causes SandMan to flee as citizens are saved.")
    elif attack2.lower().strip() == 'b':
        print("\n")
        print("You charge up and sprint towards the SandMan.")
        time.sleep(1)
        print(name, ": Here goes nothing!")
        time.sleep(1)
        print("*You charge up and hit SandMan with the meanest uppercut of all time.")
        print("He flies into the air as he was no match for your strength.")
        time.sleep(1)
        print("\n")

    # The Avengers Meeting
    print("\n")
    print("Part III: Oh Hey, It's the Avengers Now")
    print("Spider-man: Hey you! Good work out there, but what is your name?")
    print("\n")
    Heroname = input("What would you like your superhero name to be:")
    print("\n")
    print(name,": My name is",name,",but you can call me",Heroname)
    print("\n")
    print("Spider-man: Well",Heroname,"come with me, we got some work to do.")
    time.sleep(1)
    print("*You and Spider-man go to the center of town \nwhere multiple villains are wreaking havoc.")
    time.sleep(1)
    print("You arrive to see many heroes in the fight, including \nIron Man, Scarlet Witch, The Hulk, and Thor.")
    time.sleep(1)
    print("\n")
    print("Iron Man: Peter, who is this?")
    time.sleep(1)
    print("Spider-man: This is",name,"but they also go as",Heroname)
    time.sleep(1)
    print("Well kid, I hope you're ready for the fight of your life.")

    #The Final Battle
    print("\n")
    print("Part IV: The Final Battle")
    time.sleep(1)
    print("\n")
    print("Thor: Alright kid, time to go to work.")
    time.sleep(1)
    print(Heroname,": I'm ready to save New York City!")
    time.sleep(1)
    print("Scarlet Witch: That's just what we need, why don't you come with me and Hulk")
    time.sleep(1)
    print("Hulk: SMASH!!")
    time.sleep(1)
    print("\n")
    print("*Scarlet Witch, Hulk, and you head towards the northern section of town \n you end up running into Ultron, Dr. Doom, and Venom!")
    print("Scarlet Witch: I want Ultron, this is personal to me.")
    time.sleep(1)
    print("Hulk: HULK SMASH DOOM")
    time.sleep(1)
    print(Heroname,": Well, I guess I got Venom for myself.")
    time.sleep(1)
    print("\n")
    print("Venom: Fresh meat up for the taking, this'll be easy!")
    time.sleep(1)
    print("It's time to fight your first ever bad guy!")
    time.sleep(1)
    print("\n")
    print(Heroname,": Alright Venom, time for you to die!")
    print("Venom goes towards you and lands a clean swipe, cutting your face.")
    time.sleep(1)
    print("\n")
    print("What should you do to attack venom!")
    time.sleep(1)
    venom = input("A) Break Venom Down Piece by Piece\nB) Throw whatever you see at Venom and squish him. \n")
    time.sleep(1)
    print("\n")
    if venom.lower().strip() == 'a':
        print("You try to get ahold of Venom in order to break his body")
        time.sleep(1)
        print("Venom falls back after a punch and tries to come back after you.")
        time.sleep(1)
        print("Venom: You think that can stop me!")
        time.sleep(1)
        print("Venom comes back and tries to put an end to your life.")
        print("You dodge his attack and strike a punch right through the center of his back. \nHe falls and doesn't get back up with a hole in his back.")
    elif venom.lower().strip() == 'b':
        print("You start hurling anything you see towards Venom in order to take him down.")
        time.sleep(1)
        print("Multiple shots land as he begins to slow down.")
        print("Finally, you land the finishing blow as a tractor trailer takes Venom down")
        time.sleep(1)
        print(Heroname,": Not so bad for my first fight huh.")
    else:
        pass

    # The Decision
    print("\n")
    time.sleep(1)
    print("Part V: The Decision")
    print("You regroup yourself after your fight and go to help your new allies.")
    time.sleep(1)
    print("You notice both of your allies struggling to defeat their enemies.")
    time.sleep(1)
    print("\n")
    print("Scarlet Witch:",Heroname,"I need your help!")
    print("Hulk: HULK NEED HELP!!")
    time.sleep(1)
    print("There may be time to help both of your allies, \nbut you may only be able to save one.")
    time.sleep(1)
    print("\n")
    savior = input("A) Save Hulk \nB)Save Scarlet Witch \n")

    #Save Hulk
    if savior.lower().strip() == 'a':
        print("\n")
        print(Heroname, ": I'm coming Hulk!")
        time.sleep(1)
        print("You charge after towards Doom to save Hulk as Doom is flung into another dimension")
        time.sleep(1)
        print("However, you turn around to see Ultron strike a laser through Scarlet Witch's chest")
        time.sleep(1)
        print("She drops to the ground, lifeless, while you stand there in shock.")
        time.sleep(1)
        print(Heroname,": This, this is my fault.")
        print("Hulk: We must go")
        time.sleep(1)
        print("\n")
        print("You and Hulk regroup with Spider-man, Iron Man, and Thor")
        time.sleep(1)
        print("Iron Man: Where is Wanda?")
        time.sleep(1)
        print(Heroname,": I...I..could not save them both.")
        print("Iron Man: Jesus kid, it's not your fault.")
        print("Thor: You did everything you could have.")
        time.sleep(1)
        print("With Doom and Venom gone, there's 2 less villains to worry about.")
        print("What comes next though?")
        time.sleep(1)
        print("Spider-man: We gotta finish this fight!")
        print("Thor: You're right, let's end this once and for all.")

    # Save Wanda
    if savior.lower().strip() == 'b':
        print("\n")
        print(Heroname, ": I'm coming Scarlet Witch!")
        time.sleep(1)
        print("You tear down a piece of debris and hurl it towards Ultron to save Wanda as you cause Ultron to split in half")
        time.sleep(1)
        print("However, you turn around to see Doom stomp on Hulk's face, ending his life.")
        time.sleep(1)
        print("His body lays there, lifeless, while you stand there in shock.")
        time.sleep(1)
        print(Heroname,": This, this is my fault.")
        print("Scarlet Witch: We must go")
        time.sleep(1)
        print("\n")
        print("You and Wanda regroup with Spider-man, Iron Man, and Thor")
        time.sleep(1)
        print("Spider-man: Where is Hulk?")
        time.sleep(1)
        print(Heroname,": I...I..could not save them both.")
        print("Iron Man: Jesus kid, it's not your fault.")
        print("Thor: You did everything you could have.")
        time.sleep(1)
        print("With Ultron and Venom gone, there's 2 less villains to worry about.")
        print("What comes next though?")
        time.sleep(1)
        print("Spider-man: We gotta finish this fight!")
        print("Thor: You're right, let's end this once and for all.")
    else:
        pass

    ## The End?
    print("\n")
    time.sleep(1)
    print("Part VI: The End?")
    time.sleep(1)
    print("Iron Man: Alright guys let's end this once and for all.")
    time.sleep(1)
    print("\n")
    print("Green Goblin: Not so fast Iron Man!")
    time.sleep(1)
    print("Green Goblin: Did you think this would be easy?")
    time.sleep(1)
    print("Iron Man: You're going down Goblin!")
    time.sleep(1)
    print("Green Goblin: You may have defeated me last time, but this time will be different!")
    time.sleep(1)
    print("Thor: Time to go to battle, you ready",Heroname)
    print("Green Goblin: Now hold on! Why don't you come fight with us",Heroname)
    time.sleep(1)
    print("Green Goblin wants you to join them, but you wouldn't turn bad, Would you?")
    print("\n")
    evil = input("A) Join the Villains \nB) Stay on the side of Good \n")

    #Evil Ending
    if evil.lower().strip() == 'a':
        print("\n")
        time.sleep(1)
        print(Heroname,": Time to fulfill my destiny, I'm on your side Goblin.")
        time.sleep(1)
        print("Green Goblin: That's my boy!")
        time.sleep(1)
        print("Iron Man: You'll really just betray us like that kid!")
        print("Thor: Guess we'll just have to kill you too!")
        time.sleep(1)
        print("\n")
        print("You, Green Goblin, and the freed villains take on the remaining avengers. \nOne by one you are able to take down the remaining avengers, \nputting an end to the heroes in New York.")
        time.sleep(1)
        print("Green Goblin: Great Job,",Heroname,"time to take this city over!")
        time.sleep(1)
        print("You and the villains destroy NYC and take over, \nforcing innocent civilians to obey your every rule")
        time.sleep(1)
        print("The Avengers were no more, and you lived the rest of your life with power.")
        time.sleep(1)
        print("\n")
        print("The End.")

    #Hero Ending
    if evil.lower().strip() == 'b':
        print("\n")
        time.sleep(1)
        print(Heroname, ": I'd never join someone with the likes of you Goblin!")
        time.sleep(1)
        print("Green Goblin: Suit Yourself.....Kill Them All!!")
        time.sleep(1)
        print("Avengers: Alright team, let's end this!")
        time.sleep(1)
        print("\n")
        print("You and the remaining Avengers go against the rest of the villains. \nOne by one you defeat and stop villain after villain.")
        time.sleep(1)
        print("After locking up the rest of the villains, you and the Avengers have successfully saved the day.")
        print("Iron Man: Not too bad kid, I think we have a spot for you on the team.")
        time.sleep(1)
        print(Heroname, ": You...you mean it?")
        time.sleep(1)
        print("Iron Man: Ah what the hell, your an Avenger now!")
        time.sleep(1)
        print("\n")
        print("You are now officially an Avenger, and you vowed to save the city until the death of you.")
        time.sleep(1)
        print("\n")
        print("The End.")

#Magic
if power.lower().strip() == 'c':
    print("\n")
    print("Your fingers start to glow as well as your eyes.")
    print(name,": What the hell is happening??")
    time.sleep(1)
    print("You shake your hands only to turn your trash can into a basketball.")
    time.sleep(1)
    print(name,": Woah! Do I have magical abilities??")
    time.sleep(1)
    print("\n")
    print("You turn a sheet into a cape and transform yourself into a wizard.")
    time.sleep(1)
    print("Just then, you hear the news broadcast.")
    time.sleep(2)
    print("\n")
    print("Anchorman: 'Citizens of New York, be alert! \nThere has been a jail break and there are villains on the loose!")
    print("You put on your suit and head straight outside to save the city!")

    print("\n")
    print("As you get outside, you see multiple villains wreaking havoc.")
    print("You see Spider-Man villain, SandMan terrorizing civilians.")
    time.sleep(1)
    print(name, ": I gotta do something!")
    time.sleep(1)
    print(name, ": Aw man what should I do!")
    time.sleep(1)

##Magic Combat
attack3 = input("a) Cast a Shrinking Spell \nb) Hit him with a Magic Beam\n")
if attack3.lower().strip() == 'a':
    print("\n")
    print(name, ":Take this SandMan!")
    time.sleep(2)
    print("*You shrink the civilian next to SandMan")
    time.sleep(1)
    print("You try again, this time succesfully shrinking Sandman.")
    print("You run up and squish Sandman like a bug.")
elif attack3.lower().strip() == 'b':
    print("\n")
    print("You charge up fire a beam of magic towards Sandman.")
    time.sleep(1)
    print(name, ": Here goes nothing!")
    time.sleep(1)
    print("*You charge up and hit SandMan with the meanest magic beam of all time.")
    print("He disappears into thin air as he was no match for your Magic.")
    time.sleep(1)
    print("\n")
    


# The Avengers Meeting - Magic
print("\n")
print("Part III: Oh Hey, It's the Avengers Now")
print("Spider-man: Hey you! Good work out there, but what is your name?")
print("\n")
Heroname = input("What would you like your superhero name to be:")
print("\n")
print(name,": My name is",name,",but you can call me",Heroname)
print("\n")
print("Spider-man: Well",Heroname,"come with me, we got some work to do.")
time.sleep(1)
print("*You and Spider-man go to the center of town \nwhere multiple villains are wreaking havoc.")
time.sleep(1)
print("You arrive to see many heroes in the fight, including \nIron Man, Scarlet Witch, The Hulk, and Thor.")
time.sleep(1)
print("\n")
print("Iron Man: Peter, who is this?")
time.sleep(1)
print("Spider-man: This is",name,"but they also go as",Heroname)
time.sleep(1)
print("Well kid, I hope you're ready for the fight of your life.")


#The Final Battle - Magic
print("\n")
print("Part IV: The Final Battle")
time.sleep(1)
print("\n")
print("Thor: Alright kid, time to go to work.")
time.sleep(1)
print(Heroname,": I'm ready to save New York City!")
time.sleep(1)
print("Thor: That's just what we need, why don't you come with me and Tony")
time.sleep(1)
print("Iron Man: Yeah, we'll show you some pointers kid.")
time.sleep(1)
print("\n")
print("*Iron Man, Thor, and you head towards the northern section of town \n you end up running into Ultron, Dr. Doom, and Venom!")
print("Iron: I want Ultron, i created him, time for me to end him.")
time.sleep(1)
print("Thor: I'll take the bloody metal man.")
time.sleep(1)
print(Heroname,": Well, I guess I got Venom for myself.")
time.sleep(1)
print("\n")
print("Venom: Fresh meat up for the taking, this'll be easy!")
time.sleep(1)
print("It's time to fight your first ever bad guy!")
time.sleep(1)
print("\n")
print(Heroname,": Alright Venom, time for you to die!")
print("Venom goes towards you and lands a clean swipe, cutting your face.")
time.sleep(1)
print("\n")
print("What should you do to attack venom!")
time.sleep(1)
venom = input("A) Cast a spell of Weakness, making Venom vulnerable\nB) Cast a spell to make yourself Giant. \n")
time.sleep(1)
print("\n")
if venom.lower().strip() == 'a':
    print("You send a spell of weakness towards Venom.")
    time.sleep(1)
    print("Venom falls back and tries stand back up, but physically is unable to.")
    time.sleep(1)
    print("Venom: You think that can stop me!")
    time.sleep(1)
    print("Venom struggles to get up to his feet.")
    print("You form a giant fist in the air and slam it onto him. \nHe is crushed and stuck to the ground.")
elif venom.lower().strip() == 'b':
    print("You cast a growing spell and begin to get bigger.")
    time.sleep(1)
    print("You turn into the size of a two story building and kick Venom.")
    print("He goes flying into space as you shrink back down to normal size.")
    time.sleep(1)
    print(Heroname,": Not so bad for my first fight huh.")
else:
    pass

# The Decision - Magic
print("\n")
time.sleep(1)
print("Part V: The Decision")
print("You regroup yourself after your fight and go to help your new allies.")
time.sleep(1)
print("You notice both of your allies struggling to defeat their enemies.")
time.sleep(1)
print("\n")
print("Iron Man:",Heroname,"could use some help here.")
print("Thor: Care to lend me a hand here!")
time.sleep(1)
print("There may be time to help both of your allies, \nbut you may only be able to save one.")
time.sleep(1)
print("\n")
savior = input("A) Save Thor \nB)Save Iron Man \n")

#Save Thor - Magic
if savior.lower().strip() == 'a':
    print("\n")
    print(Heroname, ": I'm coming Thor!")
    time.sleep(1)
    print("You form a protection shield around Thor as Doom disinegrates as soon as he touches it.")
    time.sleep(1)
    print("However, you turn around to see Ultron strike a laser through Iron Man's chest")
    time.sleep(1)
    print("He drops to the ground, lifeless, while you stand there in shock.")
    time.sleep(1)
    print(Heroname,": This, this is my fault.")
    print("Thor: We must go")
    time.sleep(1)
    print("\n")
    print("You and Thor regroup with Spider-man, Iron Man, and Thor")
    time.sleep(1)
    print("Scarlet Witch: Where is Tony?")
    time.sleep(1)
    print(Heroname,": I...I..could not save them both.")
    print("Wanda: Jesus kid, it's not your fault.")
    print("Spider-man: You did everything you could have.")
    time.sleep(1)
    print("With Doom and Venom gone, there's 2 less villains to worry about.")
    print("What comes next though?")
    time.sleep(1)
    print("Spider-man: We gotta finish this fight!")
    print("Thor: You're right, let's end this once and for all.")

# Save Iron Man - Magic
if savior.lower().strip() == 'b':
    print("\n")
    print(Heroname, ": I'm coming Iron Man!")
    time.sleep(1)
    print("You form a protection shielf around Tony, causing Ultron to blow up on impact.")
    time.sleep(1)
    print("However, you turn around to see Doom stomp on Thor's face, ending his life.")
    time.sleep(1)
    print("His body lays there, lifeless, while you stand there in shock.")
    time.sleep(1)
    print(Heroname,": This, this is my fault.")
    print("Iron Man: We must go")
    time.sleep(1)
    print("\n")
    print("You and Wanda regroup with Spider-man, Iron Man, and Thor")
    time.sleep(1)
    print("Spider-man: Where is Thor?")
    time.sleep(1)
    print(Heroname,": I...I..could not save them both.")
    print("Iron Man: Jesus kid, it's not your fault.")
    print("Wanda: You did everything you could have.")
    time.sleep(1)
    print("With Ultron and Venom gone, there's 2 less villains to worry about.")
    print("What comes next though?")
    time.sleep(1)
    print("Spider-man: We gotta finish this fight!")
    print("Wanda: You're right, let's end this once and for all.")
else:
    pass

## The End? - Magic
print("\n")
time.sleep(1)
print("Part VI: The End?")
time.sleep(1)
print("Iron Man: Alright guys let's end this once and for all.")
time.sleep(1)
print("\n")
print("Green Goblin: Not so fast Iron Man!")
time.sleep(1)
print("Green Goblin: Did you think this would be easy?")
time.sleep(1)
print("Iron Man: You're going down Goblin!")
time.sleep(1)
print("Green Goblin: You may have defeated me last time, but this time will be different!")
time.sleep(1)
print("Spider-man: Time to go to battle, you ready",Heroname)
print("Green Goblin: Now hold on! Why don't you come fight with us",Heroname)
time.sleep(1)
print("Green Goblin wants you to join them, but you wouldn't turn bad, Would you?")
print("\n")
evil = input("A) Join the Villains \nB) Stay on the side of Good \n")

#Evil Ending - Magic
if evil.lower().strip() == 'a':
    print("\n")
    time.sleep(1)
    print(Heroname,": Time to fulfill my destiny, I'm on your side Goblin.")
    time.sleep(1)
    print("Green Goblin: That's my boy!")
    time.sleep(1)
    print("Iron Man: You'll really just betray us like that kid!")
    print("Spider-man: Guess we'll just have to kill you too!")
    time.sleep(1)
    print("\n")
    print("You, Green Goblin, and the freed villains take on the remaining avengers. \nOne by one you are able to take down the remaining avengers, \nputting an end to the heroes in New York.")
    time.sleep(1)
    print("Green Goblin: Great Job,",Heroname,"time to take this city over!")
    time.sleep(1)
    print("You and the villains destroy NYC and take over, \nforcing innocent civilians to obey your every rule")
    time.sleep(1)
    print("The Avengers were no more, and you lived the rest of your life with power.")
    time.sleep(1)
    print("\n")
    print("The End.")

#Hero Ending - Magic
if evil.lower().strip() == 'b':
    print("\n")
    time.sleep(1)
    print(Heroname, ": I'd never join someone with the likes of you Goblin!")
    time.sleep(1)
    print("Green Goblin: Suit Yourself.....Kill Them All!!")
    time.sleep(1)
    print("Avengers: Alright team, let's end this!")
    time.sleep(1)
    print("\n")
    print("You and the remaining Avengers go against the rest of the villains. \nOne by one you defeat and stop villain after villain.")
    time.sleep(1)
    print("After locking up the rest of the villains, you and the Avengers have successfully saved the day.")
    print("Iron Man: Not too bad kid, I think we have a spot for you on the team.")
    time.sleep(1)
    print(Heroname, ": You...you mean it?")
    time.sleep(1)
    print("Iron Man: Ah what the hell, your an Avenger now!")
    time.sleep(1)
    print("\n")
    print("You are now officially an Avenger, and you vowed to save the city until the death of you.")
    time.sleep(1)
    print("\n")
    print("The End.")

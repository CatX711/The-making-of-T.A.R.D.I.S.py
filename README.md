# This is the making of my probably first ever good text-based adventure game, T.A.R.D.I.S.py

## Initial idea:

*So, why did I decide to make an entier text-based game off of the spaceship named "TARDIS"? Well, it's quite funny actually. I had just finished doing my business on the toilet, when I came outside and hopped onto my bed. I remembered hearing about some person making the tardis in Minecraft. I thought to myself: 'Man, I'm bored, and I want to do some programming... Hang on a minute!*
*And the rest was history...*

# The Code:

## First Lines:

*When anyone decides to make a game, they all have to start with their first lines of code. Me, being a very unexperienced Python programmer, had very primitive lines of code. It mostly started as me doing print functions and if cmds, variables, but it all changed when I discovered the 'sleep()' function. I was trying to find a way to get the program to wait a few seconds before continuing, so it could look like the spaceship was preparing to launch or something. At first, I tried to use the 'wait' function, but that didn't do anything. I always got errors saying that, 'wait()' was not defined. Then, something in my tiny brain lit up. Why hadn't I thought of it? I just look it up. Eventually, I found a website that talked about importing 'sleep()' from 'time'. When I tried this, I was amazed. It worked! *

Probably the first lines of my code:

```
print("RUNNING 'LOADTARDIS.EXE'; PLEASE DO NOT SHUT OFF THE TARDIS MACHINE.")
sleep(6)
print("ACTIVATING ALL SAFETY PROTOCALLS...")
sleep(2)
print("56%")
sleep(0.45)
print("68%")
sleep(4)
print("100%")
sleep(1)
print("STARTING ALL SYSTEMS...")
sleep(5)
print("78%")
sleep(0.87)
print("80%")
sleep(2)
print("86%")
sleep(3)
print("97.2%")
sleep(4)
print("100%")
print("LOAD SUCCESSFUL. STARTING UP...")
sleep(7)
print("HELLO.")
print("WELCOME TO THE TARDIS. PLEASE PRESS 'xyzxx12dc' ON YOUR KEYBOARD AND HIT ENER TO OPEN HATCH AND SCAN YOUR CREW KEY (TARDIS TM.)")
scankey = input()
if scankey == "xyzxx12dc":
    print("SCANNING: 25% COMPLETE")
    sleep(3)
    print("SCANNING: 67% COMPLETE")
    sleep(2)
    print("SCANNING: 79% COMPLETE")
    sleep(4)
    print("SCANNING: 99% COMPLETE")
    sleep(7)
    print("SCANNING: 100% COMPLETE")
    sleep(1)
    print("GOOD TO SEE YOU, USER12144")
    print("WE HAVE NOTICED THAT YOU DO NOT HAVE A USER NAME. PLEASE ENTER YOUR NEW NAME AND HIT ENTER.")
    username = input()
    print("PROCESSING. PLEASE WAIT...")
    sleep(5)
    print("HOW ARE YOU LIKING YOUR NEW NAME," + username + "?")
    print("NOW THAT YOU HAVE SIGNED IN TO THE TARDIS DATABASE, WORLD12-44 EXCLUSIVE, PLEASE TELL US WHERE YOU WOULD LIKE TO GO.")
    print("LIST OF OPTIONS: 1: BACKROOMS - ASYNC INC. 2: PLANET E-456, NEBULA B3, 3: PLANET EARTH-X, CLUSTER II, LACTOSE WAY, 4: HOMEBASE, GALACTIX 55-6")
    print(" #1 = b #2 = e-456 #3 = e-x #4 = hb")
    goto = input()
    if goto == "b":
        print("TURNING ON BOOSTERS. CALCULATING DESTINATION. PREPARING EMERGENCY EXITS. PLEASE PUT ON YOUR ASYNC HASMAT SUITS, AS THIS IS A HIGHLY CONTAMINATED ZONE, FULL OF BACTERIA AND VIRUSES. BRING PROPER SAFETY EQUIPMENT, LIKE ITEMS TO REPEAR BROKEN HASMAT SUITS, SUIT CAMS AND FLAMETHROWERS.")
        print("RED WIRE TO FIND YOUR WAY BACK TO THE LAB WILL BE GIVEN TO YOU WHEN YOU GET THERE. KEEP AN EYE OUT FOR THE MUTATED BACTERIA AND DRINKABLE ALMOND WATER.")
        sleep(15)
        print("ACTIVATING CLEAROGEL. CHEKCING COOLANT SYSTEMS. STIMULATING ION DETANATION FROM FUEL CRYSTALS. FILLING FUEL TANKS. FILLING OXYGEN TANKS.")
        sleep(10)
        print("PLEASE HOLD ONTO YOUR SEATS AND PUT ON THE SAFETY STRAP. WE WILL LEAVE IN:")
        print("5...")
        sleep(2)
        print("4...")
        sleep(2)
        print("3...")
        sleep(2)
        print("2...")
        sleep(2)
        print("1...")
        sleep(3)
        print("BLAST OFF! TIME UNTIL DESTINATION REACH: 10 SECONDS.")
        sleep(5)
        print("HALFWAY.")
        sleep(5)
        print("ACTIVATING BRAKES. EJECTING FUEL CRYSTALS. RELEASING BRAKE BOOSTERS. PLEASE WAIT ANOTHER 10 SECONDS TO SAFELY LAND, WHEN WE HAVE LOST ALL FRICTION.")
        sleep(10)
        print("SUCCESSFUL LANDING. PLEASE EXIT NOW. TYPE 'goodbye_tardis' TO SHUT DOWN TARDIS. DEACTIVATING UN-NECESARY SYSTEMS TO PRESERVE POWER.")
        print("TYPE 'goback_initiate' ON YOUR KEYBOARD TO RE-START ALL SYSTEMS AND GO BACK TO YOUR HOME.")
        whatnext = input()
        if whatnext == "goback_initiate":
            print("ACTIVATING QUICK-TRAVEL V.91")
            print("PLEASE PUT ON YOUR GAS MASKS ABOVE YOUR HEADS TO BE ABLE TO BREATH DURING THE TRIP AS WE WILL BE GOING SO FAST OXYGEN WILL NOT BE ABLE TO MANUALLY ENTER YOUR LUNGS")
            print("ACTIVATING INTER DIMENSIONAL PORTAL. QUICK TRAVELING IN:")
            sleep(3)
            print("'TAKE OFF TIME' SYSTEMS FAILED. PREPARE TO LAUNCH AT ANY MOMENT.")
            sleep(4)
            print("BOOM! WE HAVE ENTERED QUICK TRAVEL. EXITING IN 3 SECONDS")
            sleep(3)
            print("BRACE FOR IMPACT. BANG. WE HAVE LANDED. READINGS SHOW THAT THE LANDING WHEELS SUSTAINED MINOR DAMAGE. FIXING NOW. YOU MAY EXIT THE TARDIS.")
        if whatnext == "goodbye_tardis":
            print("SHUTTING DOWN ALL SYSTEMS. ACTIVATING INVISIBLE CAMOFLAUGE. GOODBYE, " + username + "!")

```
*In that code, I added the tardis' takeoff sequence. I then added the first location you could travel too, 'The Backrooms' (an liminal space), and started developing the second location, planet 'e456'.

## Planet 'Eartheria Xenovia 456':

### E-X code:

*I started with simple code for E-456:*

```
 if goto == "e-456":
        print("PLANET 'e-456' IS LIKE AN ALTERNATE VERSION OF OUR UNIVERSE. IT IS LOCATED IN 'Nebula B3', AND WAS COLONISED DUE TO BEING VERY SIMILAR TO OUR PLANET. THE PLACE CONSISTS OF A MOSTLY OXYGENATED ATMOSPHERE, WITH A SWEET, SALTY LIQUID THAT MAKES UP THE SEAS CALLED, 'Liquid-42'. HOW THIS LIQUID WAS FORMED IS UNKNOWN, BUT IT IS SAFE TO DRINK.")
        sleep(21)
        print("DO NOT APROACH ANY WILDIFE THERE WHEN UNSUPERVISED, AS MOST OF THE ANIMALS, PLANTS, FUNGI HERE ARE DANGEROUS.")
        sleep(6)
        print("TURNING ON BOOSTERS. CALCULATING DESTINATION. PREPARING EMERGENCY EXITS.")
        sleep(6)
        print("ACTIVATING CLEAROGEL. CHEKCING COOLANT SYSTEMS. STIMULATING ION DETANATION FROM FUEL CRYSTALS. FILLING FUEL TANKS. FILLING OXYGEN TANKS.")
        sleep(10)
        print("PLEASE HOLD ONTO YOUR SEATS AND PUT ON THE SAFETY STRAP. WE WILL LEAVE IN:")
        print("5...")
        sleep(2)
        print("4...")
        sleep(2)
        print("3...")
        sleep(2)
        print("2...")
        sleep(2)
        print("1...")
        sleep(3)
        print("BLAST OFF! TIME UNTIL DESTINATION REACH: 10 SECONDS.")
        sleep(5)
        print("HALFWAY.")
        sleep(5)
        print("ACTIVATING BRAKES. EJECTING FUEL CRYSTALS. RELEASING BRAKE BOOSTERS. PLEASE WAIT ANOTHER 10 SECONDS TO SAFELY LAND, WHEN WE HAVE LOST ALL FRICTION.")
        sleep(10)
        print("SUCCESSFUL LANDING. PLEASE EXIT NOW. TYPE 'goodbye_tardis' TO SHUT DOWN TARDIS. DEACTIVATING UN-NECESARY SYSTEMS TO PRESERVE POWER.")
        print("TYPE 'goback_initiate' ON YOUR KEYBOARD TO RE-START ALL SYSTEMS AND GO BACK TO YOUR HOME.")
        
 ```
 
*After I finished that, I took a break and started conjuring up ideas for things in the game.*
*Eventually I intigrated a system that takes you to your homebase, called "goback_initiate", and  called a shutdown system called "goodbye_tardis", which when activated would end the program. I did this with this easy code:*

```
if whatnext == "goback_initiate":
            print("ACTIVATING QUICK-TRAVEL V.91")
            print("PLEASE PUT ON YOUR GAS MASKS ABOVE YOUR HEADS TO BE ABLE TO BREATH DURING THE TRIP AS WE WILL BE GOING SO FAST OXYGEN WILL NOT BE ABLE TO MANUALLY ENTER YOUR LUNGS")
            print("ACTIVATING INTER DIMENSIONAL PORTAL. QUICK TRAVELING IN:")
            sleep(3)
            print("'TAKE OFF TIME' SYSTEMS FAILED. PREPARE TO LAUNCH AT ANY MOMENT.")
            sleep(4)
            print("BOOM! WE HAVE ENTERED QUICK TRAVEL. EXITING IN 3 SECONDS")
            sleep(3)
            print("BRACE FOR IMPACT. BANG. WE HAVE LANDED. READINGS SHOW THAT THE LANDING WHEELS SUSTAINED MINOR DAMAGE. FIXING NOW. YOU MAY EXIT THE TARDIS.")
        if whatnext == "goodbye_tardis":
            print("SHUTTING DOWN ALL SYSTEMS. ACTIVATING INVISIBLE CAMOFLAUGE. GOODBYE, " + username + "!")

```


# This is the making of my probably first ever good text-based adventure game, T.A.R.D.I.S.py

## Initial idea:

*So, why did I decide to make an entier text-based game off of the spaceship named "TARDIS"? Well, it's quite funny actually. I had just finished doing my business on the toilet, when I came outside and hopped onto my bed. I remembered hearing about some person making the tardis in Minecraft. I thought to myself: 'Man, I'm bored, and I want to do some programming... Hang on a minute!*
*And the rest was history...*

# The Code:

## First Lines:

*When anyone decides to make a game, they all have to start with their first lines of code. Me, being a very unexperienced Python programmer, had very primitive lines of code. It mostly started as me doing print functions, 'if' cmds, and variables, but it all changed when I discovered the 'sleep()' function. I was trying to find a way to get the program to wait a few seconds before continuing, so it could look like the spaceship was preparing to launch or something. At first, I tried to use the 'wait' function, but that didn't do anything. I always got errors saying that, 'wait()' was not defined. Then, something in my tiny brain lit up. Why hadn't I thought of it? I just look it up. Eventually, I found a website that talked about importing 'sleep()' from 'time'. When I tried this, I was amazed. It worked!*

Probably the first lines of my code:

```
print("RUNNING 'LOADTARDIS.EXE'; PLEASE DO NOT SHUT OFF THE TARDIS MACHINE.")
sleep(6)
print("ACTIVATING ALL SAFETY PROTOCOLS...")
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
*In that code, I added the tardis' takeoff sequence, and then added the first location you could travel to, 'The Backrooms' (an internet liminal space), and started developing the second location, planet 'e-456'.*

## Planet 'E-456':

### Th-E code: (get it? The e in 'the' is the 'e' in 'e-456'!)

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
 
*After I finished that, I took a break and started conjuring up ideas for things in the game. Eventually I intigrated a system that takes you to your homebase, called "goback_initiate", and  called a shutdown system called "goodbye_tardis", which when activated would end the program. I did this with this easy code:*

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
*That's E-456 done, so, onto the next location!*

## Eartheria Xenovia 46

### Xenovi Coding

*Eartheria Xenovia 456 (prounounced urth-eer-ia cse-no-vee-a 46), or, more commonly known as Earth-X, is, as the code says, is a barren wasteland. On the way there the tardis gets jumped and destroyed by an intergalactic monster. This idea was cool, but I originally wanted to make the monster only have a 35% chance of killing you. Of course, because I suck, I had no idea how to do this, and gave up, making the monster kill you every time you go there. What a sad, sad life.*

*The code I used:*

```
if goto == "e-x":
        print("EARTHERIA XENOVIA 46, MORE COMMONLY KNOWN AS EARTH-X, IS A WASTELAND, WITH A HIGHLY TOXIC ATMOSPHERE, ACID RAIN, HIGH PRESSURE, EQUIVALENT TO SWIMMING A FEW MILES UNDERWATER, AND A BAREN, ROCKY LANDSCAPE. THE ONLY GOOD THING ABOUT THIS PLANET IS HOW MINERAL RICH IT IS.")
        print("DUE TO THE CONDITIONS OF THE PLANET, WHEN EXITING THE TARDIS, YOU MUST WEAR A HIGHLY PROTECTIVE, CLASS 18 M.U.C EXTREME ENVIRONMENT SUIT (C18_M.U.C_E.E.S)")
        print("WHEN LANDED, THE TARDIS WILL NOT SHUT OFF, AS IF THE SYSTEMS ARE DISABLED, THE OUTER LAYER OF THE SHIP WOULD MELT, LEAVING THE FRAGILE PARTS EXPOSED. THERE WILL BE NO BREATHABLE AIR HERE, SO BE WEARY. WHEN YOU EXIT THE TARDIS, RUN AS FAST AS YOU CAN, AS GOING SLOWLY WILL DAMAGE THE SUIT FROM THE CONDITIONS.")
        print("PLEASE DO NOT EXIT THE BASES THAT YOU WILL ENTER WHEN YOU LAND ON THIS WORLD, AS YOU WILL EASILY BE DECIMATED BY THE WEATHER. GOOD LUCK!")
        sleep(55)
        print("TURNING ON BOOSTERS. CALCULATING DESTINATION. PREPARING EMERGENCY EXITS.")
        sleep(2)
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
        sleep(10)
        print("DETECTING THREAT... PLEASE WAIT. SCANNING...")
        sleep(3)
        print("IDENTIFYING THREAT:")
        print("PREFORMING RADIOWAVE SCAN...")
        sleep(4)
        print("idinfijsndiusdnfincisiunin12uinuiniudnisuncnijdncisdncishbcubsiuysudygbugbubSDSEFDVDVJDSD__BESFHNSDHFIDNIUDIAWHD-NJDNIUNDASJN-DLNDIAJSDN-AJSNDKAJSDNAKJSDNISFNIMUWU12354dgchnchdndhdhdhgfbcgfmjlkpolkpollaolpoldlpoasewrgdg11nnnbjn2hh3hhdhnchsdshnjsnjchsncjhbscjhsncjsjfjfueuehudhcidjhijii-456796869724352jdjjdjdfnccnnindiwnjnuhbbihiuiuhiuhiygfgadgnjdcdmcoscosmcos________bhbhbh12bhbuhbucnu89nxndcuncusncusncusncusncbhn46bhbcjhdjhbsjhbhbcnejkdjnkdjncjdnccnnxbshishuhcuhhdnicjncincjnjnjnjnhhysbgsbdghnjdnd000990099999900990010100000111100020002ijijj-7-8-6-7-8-9-ujijidhshbuabduyasduyhsudy'#~~~~///////????!##~~~~hdusiudh~##############123jdsujdsu45dhhnhnc76uhsduhsd8jjj0")
        sleep(1)
        print("udhushduhsudhsjdna#udyhaudyhasuydhsuydhayushday--- #12366 LOCATED.")
        sleep(2)
        print("RADIOWAVE SCAN COMPLETE.")
        print("THREAT IDENTIFIED.")
        print("PLEASE EXIT TO YOUR LIFE PODS, AS AN UNKNOW SPECIES HAS ENTERED THE SHIP.")
        sleep(5)
        print("*WARNING* *WARNING* AN ALIEN SPECIES HAS ENTERED THE SHIP- PLEASE EVACUATE TO THE LIFE PODS LOCATED ON HALLWAY 678, 899, 432, 106. THIS MESSAGE WILL NOW REPEAT!")
        sleep(2)
        print("*WARNING* *WARNING* AN ALIEN SPECIES HAS ENTERED THE SHIP- PLEASE EVACUATE TO THE LIFE PODS LOCATED ON HALLWAY 678, 899, 432, 106. THIS MESSAGE WILL NOW REPEAT!")
        sleep(2)
        print("*WARNING* *WARNING* AN ALIEN SPECIES HAS ENTERED THE SHIP- PLEASE EVACUATE TO THE LIFE PODS LOCATED ON HALLWAY 678, 899, 432, 106. THIS MESSAGE WILL NOW REPEAT!")
        sleep(2)
        print("*WARNING* *WARNING* AN ALIEN SPECIES HAS ENTERED THE SHIP- PLEASE EVACUATE TO THE LIFE PODS LOCATED ON HALLWAY 678, 899, 432, 106. THIS MESSAGE WILL NOW REPEAT!")
        sleep(2)
        print("EJECTING LIFE PODS. ACTIVATING DEFENSE SYSTEMS. RELEASING POISONOUS GASSES. ALL CREW, PLEASE PUT ON YOUR GAS MASK AS YOU EVACUATE TO THE LIFE PODS. RUNNING SELF DESTRUCTION PROGRAMME.")
        print("RUNNING:")
        sleep(1)
        print("5%")
        sleep(5)
        print("26%")
        sleep(4)
        print("56%")
        sleep(3)
        print("78%")
        sleep(2)
        print("81%")
        sleep(2)
        print("99.98%")
        sleep(2)
        print("99.99%")
        print("100%")
        print("SELF DESTRUCTION IN 3... 2... 1...")
        sleep(1)
        print("SELF DESTRUCT INITIATED.")

```
*After this, I took a brake from coding TARDIS for a bit.*

### The next day was A-Okay!:

*After the previous day, I wanted to add the final location: The Homebase. So I got to work.*

```
if goto == "hb":
        print("HOMEBASE IS WHERE YOU LIVE, WHERE TARDISES ARE BUILT, AS WELL AS MARK-45 TARDI, AND WHERE RESEARCH IS DONE ON PLANETS AND GALAXYS, ECT. ONCE AT HOMEBASE YOU HAVE THE OPTION TO TRAVEL TO YOUR HOME PLANET.")
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
```
*At this time I went cry cry, as I realised this was nearly the end of my project, and my computer went boom boom from the amount of code it was having to run.*

```
sleep(5)
        print("HALFWAY.")
        sleep(5)
        print("ACTIVATING BRAKES. EJECTING FUEL CRYSTALS. RELEASING BRAKE BOOSTERS. PLEASE WAIT ANOTHER 10 SECONDS TO SAFELY LAND, WHEN WE HAVE LOST ALL FRICTION.")
        sleep(10)
        print("SUCCESSFUL LANDING. PLEASE EXIT NOW! BYE!")
        sleep(2)
        print("SHUTTING DOWN.")

```
*Is this it... the end?! No, it's not. I did a lot more freaking work.*

## Final touches... ish:

*At this point I was working on polishing the game and fixing bugs. I added TerraBot, who activates the tardis, and fixed some errors. My 11 year old brain was deflated at this point. I added clocation and scankey, to verify your location and stuff like that, and wrote my last lines of code.*

# THE END (not really):

*As I hit the final letters on my keyboard, I shed a single tear... and, also... immediately uploaded it onto github. if you would like to see the full code, look at the second file in this repository. Thanks for reading this (sort of) book!*

# The actual end:

*I will probably come back to this game in some time. I'm already working on a sequel! But currently, tardis.py will be left alone. If you would like to try it, just fork the code. Anyways, have a good day/night, my fellow githubbers! (or is it githubi...-Never mind that, no one cares!)*



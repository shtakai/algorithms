# 1
1) Your friend is building a portal like game where creatures can jump through portals to get to the player.  The creatures are stored in an array, as objects: e.g: [{creature:"Morgran", x:100, y:100}, {creature:"Grubnor", x:50, y:50}].  The portals don't transport creatures to a new portal, but rather multiply, and reset the creature's x and y coordinate by a new value (the creature can then move, but the x and y coordinates don't change).  Write a portal function that takes a the creature array and a variable (the multiplier) and a creature name and appropriately adjusts the position: e.g.
```
portalFunction(critterArray, -0.5, "Grubnor")
```  
and the array would now look like:  
```
[{creature:"Morgran", x:100, y:100}, {creature:"Grubnor", x:-25, y:-25}]
pts: 5
```
# 2
You and a friend were super bored and wanted to make a Russian Doll emulator:  When someone click's the button next to the doll saying value: the doll spins around and shows a value.  When someone click's on the doll itself.  It opens up and if there is another doll inside, that doll will show up, otherwise a flag pops up saying: no more dolls!  As doll administrators, you want to be able to add a new doll to the outer shell...
Implement the back end code for your Russian Doll emulator. (feel free to implement it into a webpage if you want!)
###### pts: 8
###### pts: 14 for a webpage

# 3  
Your teacher friend wants to make a quick app to sort his students by their grades (all of which are between 0 and 100, with at most 1 decimal pt).  All of his colleagues love this idea, and they want to sort the students by grade,regardless of class -- but one of them thinks it'd be awesome to extend this across the nation.  (You scoff at this idea, but whatever, you are pretty sure you can do this if they give you an array of {students:"name",grades:"val"}, and only go through the array a few times to do it... no nested loops)

###### pts: 8

#4
Another friend wants you to build a game: the game board has randomly generated doors (0s) and is a m by n rectangle.  He wants you to write an algorithm that if a player were to spawn somewhere, that your program would find the shortest route to the nearest door.
e.g.:
###### [
###### [x,x,x,<,<,<,player,x],
###### [x,x,x,|,x,x,x,x],   
###### [x,x,x,0,x,x,x,x],   
###### [x,x,x,x,x,x,x,x],   
###### [x,x,x,x,x,x,x,x],   
###### [x,x,x,x,x,x,x,x]
###### ]  
pts: 30

# 5
You are at an interview and your interviewer wants to reward her team.  She gives you a stack of $20 bills and says, you've got the job, but only if can tell me how many 20's I've given you.  You start counting them, but she says: "Oh, and you can't count them, you have to give them all to one employee and can only talk to that employee, and all of my employees only have time to count 1...but can tell you (or anyone else) a number"  When you give the stack of 20's to an employee, what do you tell that employee such that he tells you later in the day how many 20's she gave you?

###### pts: 10

# 6
You are given 10 water balloons that you want to drop on your 8 friends.  They are all exactly the same.  You don't want  to hurt your friends, but you want to make sure that the water balloon pops, because it's the worst when the balloon doesn't pop and then your friend hits you with it!  You are going to drop them from a 100 story building (and they will all break when dropped from, or above an arbitrary floor), but you don't want to kill your friends, so you want to drop them from the lowest floor you can.  How would you figure out the lowest floor you can drop them from, while still having 8 balloons to drop on your friends?  How few trials can you do?

###### pts: 5-10

# 7
You like pretty, random patterns (ooh shiny objects):  Implement an algorithm that recursively fans out a number of times between 0 and 10.  Each branch then goes out a random distance distance between 10 - 30 pixels, and once it ends that distance it branches between 0 and 9...  This repeats but the next branch goes 0 and 8... This repeats for 0 and 7... until there are no more branches to fan out.  (To make it pretty, have angle for each branch change by a fixed # of degrees)
###### pts 15 for implementing it
###### pts 10 for making it graphical
###### pts 20 for finding the average longest path from this thing

# 8
You just joined a basketball team (just 15 players), you're given a new jersey number. Unfortunately you don't know your teammates that well. However you are given access to a Binary Search Tree containing everyone's jersey number on the team and their name. Get to know the players' names who have the jersey number that is directly (the numerical value closest to yours, but greater than yours) above you and directly below you (the numerical value closes to yours but less than yours)! How would you find them?  Implement an algorithm for solving this!

###### pts: 30.

# 9
You and your significant other are out running in a really dense fog.  You've told one another that if you get separated, just take all the right turns you can (since you are on a city block, but an unknown city).  Invariably you get separated, fortunately you know exactly how fast you both run.  Write an algorithm that calculates the distance around the city block.  What if your running course was on a weird path, where there was a one way gate (so you both run by it on the outward bound direction, but then make a P) and loop through just the loop of the p.  Can you figure it out the length of the loop of the p? How about the stem of the p (from start to the gate).  Write an algorithm to demonstrate this!

###### pts: 10 for basic cityblock loop
###### pts: 20 for the loop with a stem. (e.g. a P)

#10
In a group of people(represented as an array) each person either has a key or a lock. There are only three types of keys and locks(red,blue,green). A lock of type green can be opened by any green key and so on for the other types. In this group if we pair all locks and keys that match together figure out if there are any extra keys or locks that do not match up and if so state whether there are too many locks or too many keys.

e.g: [greenKey, greenLock, greenKey, redKey, redLock]

###### pts: 10

#11
You wake up one day and discover that you have suddenly been given the position of Mayor of Townsville. In Townsville every building is only 1 unit wide, but they have various heights. So you start you day, sit down at your nice oak desk, say "Good-Morning" to your lovely secretary, and begin working through the tasks at hand. The first task you come across was requested by the Mathematician's Guild and lists the heights of buildings of the city in an array. They are asking if you could figure out the largest rectangle that can be created by one or more consecutive buildings in the array. Being the fantastic mayor that you are, you set out to devise an algorithm to tackle this problem for any arrangement of the buildings.

###### pts: 20

# 12
There are N plants in a garden. Each of these plants has been given some amount of pesticide. After each day, if any plant has less pesticide than the plant to its left, being weaker than the left one, it will die. Given an array of pesticide values for each plant in order, how many days will pass before no further plants will die?

###### pts: 20

# 13
Joe drives a taco truck in Squaresburg.  To navigate, everyone in Squaresburg uses x,y coordinates!  Blocks are perfect squares and every street is two-way, at perfect right angles.  Joe (and everyone in Squaresburg) is a bit communist, and wants to minimize the total distance anyone (as a sum) needs to go to get a taco.  Write an algorithm to figure out where Joe should park:

Example: People are at [[10,0], [-1,-10], [2,4]], you should return [2,0] for the location of Joe's truck!

###### pts: 15
#14
A **giant slime monster** dunh dunh dunh, has crash landed on the Earth and splattered into various blobs.  These little blobs all have varying toughness, that represent their resilience to explosions.  After the crash, the monster's smaller blobs start to clump together (and their toughness's sum!) -- and the military IS NOT cool with that, and decide to nuke the re-forming blobs.  The blob can only merge the two weakest at a time.  If given enough time, the Military could fail, because all the smallest blobs are all tough enough to survive a blast!   Oh SNAP!

You are given the state of the monster after the initial crash by toughness e.g. [5,29,4,47,12] and the strength of a nuke.  (60)  Write an algorithm to determine the fewest nukes to eradicate the whole monster? e.g. 2 for the monstrous event above.
###### pts: 20

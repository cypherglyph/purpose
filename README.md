# Purpose of this git
This is my first git repo, initially I'm going to use it to design my game, I'm a Scottish Programmer (not a games programmer but I'm learning) I have experience with C#, Java, Python and a few more but none worth mentioning.

Consequently - I'm going to try to create a game themed around the idea of 'programming' - I have no doubt it won't be much of a success but it's a start and it might get me ready to try a Game Jam or something.

Wish me luck!


#The Game
_(It doesn't have a name yet)_

* Really shallow learning curve however aiming for 'infinite replayability'
* Desktop/Web - probably Unity (C#)
* Turn-Based Strategy (sort of)
* 'Programming' will be simple - building a rules based or decision tree structure which is evaluated when it's that entity's turn - but able to generate complex behaviours - this has a nice side-effect of drastically simplifying AI - which i'm not very good at
* Current Setting - Sci-Fi, spaceships
* Mechanics - Player 'programs' each ship in his/her fleet, battles are automated using these scripts
* Grid/Hex battlefield with Environmental entities (Asteroids, nebula, etc)
* Fairly complex battle system/programmable actions (buffs/debuffs, abilities, multiple damage types [rock-paper-scissors-etc-etc] environmental effects, limited time manipulation?)
* Initially player will control 1-2 ships but more ships will be added on progress
* Tutorial style first levels
* May spawn future sequels of increasing complexity as I've drawn lines under many aspects of this game's functionality that I would like to expand in future but preserving this game rather than adding to it would allow for a graduated educational theme running through a potential game series
* I have a plot, it's not a very good one but there you go...


##The Game



###Programming

Where actions, conditionals and logic are encapsulated...
* An 'If Statement' has a Conditional statement plus a true statement and a false statement, the statement to be evaluated is determined by the result of evaluating the Conditional
* Retrieval statement get's a value from an entity
* Operation statement performs an Operation on a Value or Values
* Action - Attack, Use Ability, etc.
* A Value holds a value, it's also potentially a return object.
* A Constant is just a fixed value(?)
* A Target statement {
NearestEnemy
NearestFriendly
NearestNeutral
}
* Function statement(?)
* Expression statement?
* Globals? Lists? {
AllTarget?
AllEnemy?
AllFriendly?
AllNeutral?
AllEnvironmental?
}
*LOGIC statements?
{
AND
OR
NOT
}
[Only able to accept statements that return Bools - see Conditionals]

Ok, 'default' program will be...

Attack(NearestTarget) or in type-speak Action(Target)

Next will be...

//Movement?

Conditionals? 

IF(EQUALS(GET(NearestTarget,IsEnemy), TRUE), Attack(NearestTarget), NULL)

Conditional(Operation(Retrieval(Target, Attribute), Value), Action(Target), Special/Value/Constant?)


As you can see - work in progress - whatever the player intreracts with to code will parse itself into an expression tree made of the above types of objects which will be attached to the Entity which will then evaluate it at runtime. The Entity will have access to itself, the map and probably a few useful collections - there are a lot of things I would like to 

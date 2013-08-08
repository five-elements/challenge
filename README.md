The Five Elements Challenge
===========================
The five elements are five essential and fundamental game archetypes that are 
milestones in video game history. As a hobbyist game programmer I think a
worth while right of passage is to implement each archetype in order to conquer 
a specific problem domain. It's a little bit like Luke Skywalker's Jedi training 
culminating in the creation of his own Light Saber. By the end of the five 
challenges the programmer will have accumulated a body of knowledge and code to 
wield as a weapon in the face of mental confrontation.

The Elements
============
Each element is a building block in the quest for game code mastery. Here they
are listed in (expected) order of increasing difficulty.

    Side notes are listed like this and mostly act as justification for
    the choices I've made below.

For each challenge some concepts are required and some are optional. Generally
the more optional concepts the student chooses to implement the harder the 
challenge will be. On the flipside, choosing more optional concepts early on
may better prepare the student for the next step, which in the long run may make 
the harder challenges more attainable. Essentially they choose when to suffer. 

The Text Adventure
------------------
The text adventure is a game distilled down to its core. Technically it can be 
interpreted as a simple [REPL](https://en.wikipedia.org/wiki/REPL). Input is
supplied on the command line and rendering happens on the command line. It can 
be as basic as a 'choose your own adventure' interactive novel. 

[Wikipedia](https://en.wikipedia.org/wiki/Text_adventure "Text_Adventure")

    I'm pretty sure this should be first as it takes the least amount of
    graphics knowledge. Programmers of most langs will be able to finish
    this challenge without external libs, etc.

#### Concepts ####
 * Input 
    - Keyboard
 * Turn based time
 * Text rendering

#### Examples ####
 * Zork
 * The Hobbit
 * The Hitchhiker's Guide to the Galaxy

The Roguelike
-------------
A roguelike is a dungeon crawler. It introduces the concepts of procedural 
generation of content and at least slightly more complex rendering, either
graphically or in text. The gameplay can be turn-based or continuous, which
gives the student a choice in how fast the rate of programming difficulty 
increases. A turn-based, text roguelike doesn't have to be much more difficult
than the text adventure but if the student wants to ramp up fast they can 
tackle the continuous graphical version.

[Wikipedia](https://en.wikipedia.org/wiki/Roguelike "roguelike")

    A roguelike is so diverse in its implementation that I think it's
    a great second step. It has a lot of slack with regard to how fast 
    the student wants to learn new concepts. 

#### Concepts ####
 * Input 
    - Keyboard
    - Mouse (optional)
 * Turn based time
 * Continuous time (optional)
 * Text rendering
 * Graphical rendering (optional)
 * Axxonometric projection (optional)
 * Procedural content generation
    - Maps

#### Examples ####
 * Rogue
 * Gauntlet
 * Diablo

The Arcade Classic 
------------------
The arcade classic can take the form of many combinations of gameplay.
At its core it is a game that is rendered graphically and time is treated
continuously. The player must be constantly engaged and reacting to events
unfolding on the screen. It usually involves some amount of hit testing for
things like projectiles, but not so much as to necessitate an entire physics 
system. Sprite animation is an advanced track theme, as well as affine 
transformations. At this point as text-mode is not an option and sound was 
a vital part of these arcade games, sound should be a requirement, but sound
is really hard on some langs/platforms (I'm looking at you, Haskell) so sound 
will always be optional and set to the 'advanced' track.

    Pong seems like the simplest game that includes input, time, and graphics 
    rendering, though it may be too easy and won't prepare the student for the
    next step. Something like space invaders would be a good mid track choice.
    For the advanced track I'm thinking Zaxxon, since it would have to use 
    some 3D math for hit testing and the isometric z-sorting could be a big
    challenge.

#### Concepts ####
 * Input
     - Keyboard
     - Mouse (optional)
 * Continuous time
 * Graphical rendering
 * Hit testing / Collision
 * Physics (optional)
 * Sprite animation (optional)
 * Axxonometric projection (optional)
 * Sound (optional)

#### Examples ####
 * Asteroids
 * Breakout
 * Tetris
 * Space Invaders / Galaga
 * Zaxxon
 * Street Fighter 2

The Platformer
--------------
The flagship genre of 1990's consoles, the platformer dominated the industry
for [nearly a decade](http://www.gamasutra.com/view/feature/130268/a_detailed_crossexamination_of_.php?page=2).
Platformers rely heavily upon sprite based animation, collisions and physics
systems. This makes it a natural progression up from the arcade classic which
optionally employs those concepts. The challenge can be made harder by 
experimenting with novel character control schemes or artificial intelligence,
etc.
    
    Some notes would be good here.

#### Concepts ####
 * Input
    - Keyboard
    - Mouse (optional) 
    - Joystick / Gamepad (optional)
 * Continuous time
 * Graphical rendering
 * Sprite animation
 * Hit testing / Collision 
 * Physics
 * AI (optional)
 * Sound (optional)

#### Examples ####
 * Super Mario Bros
 * Sonic the Hedgehog
 * Another World / Flashback

The First Person Shooter
------------------------
The last step of the challeng is the first person shooter. It is the most 
complicated part of the challenge and is arguably the current state of the art 
of game programming. The FPS is a big step up from the platformer. It uses all of the former 
concepts but takes them into the realm of 3D. 

    A working implementation could be as simple as Wolfenstein 3D, though 
    in my opinion I think that's still pretty complex. To reduce the complexity 
    the student could strip out the physics and just use some simple hit 
    testing. 

#### Concepts ####
 * Input 
    - Keyboard
    - Mouse (optional)
    - Joystick / Gamepage (optional)
 * Continuous time
 * Graphical 3D rendering
 * Sprite animation
 * Hit testing / Collision
 * Mesh animation (optional)
 * Physics (optional)
 * AI (optional)
 * Sound (optional)

#### Examples ####
 * Wolfenstein 3D
 * Quake
 * Halo
 * Portal

How to Participate
==================
If you'd like to participate in The Five Elements Challenge just fork this repo 
to your github and start hacking. There's no prizes, deadlines or authorities. 
There are only students, a feeling of accomplishment and the comaraderie of 
those other fellows of the five elements :)

Notes
-----
I've included some files for pre and post mortems for each element. Feel free 
to add your thoughts on what went wrong or right along the way. Most of all
have fun learning!

Resources
---------
Here would be a good place to do a pull request with links to high quality 
articles on game programming in general. The more language and paradigm 
agnostic the better!


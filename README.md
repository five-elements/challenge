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
 * Procedural content generation
    - Maps

The Arcade Classic 
------------------
    Pong, Breakout, etc. Pong seems like the simplest game that includes
    input, time, and graphics rendering. 

The Platformer
--------------
    Definitely an element and somewhat complex at that.

The First Person Shooter
------------------------
    The most complicated element and the current state of the art game 
    genre.

How to Participate
==================
If you'd like to participate in The Five Elements Challenge just fork this repo 
to your github and start hacking. There's no prizes, deadlines, authorities or 
rockstars. There are only students, a feeling of accomplishment and the 
comaraderie of those other fellows of the five elements :)

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


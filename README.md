# - Pong Game -

<h2> Description </h2>

I coded my own game loosly based of pong mechanics. As someone who enjoys games I thought it would be a good strating point to build coding experience and skills outside of my University course.

Bellow I have presented images of the game itself, and the code used to make the game. At the end is a more indepth analysis of the project and what i learned from it, the challanges i faced and any reflections I've had after making theh game. 

<h2> Languages Used </h2>
 - Python 

<h2> Game Itself </h2>
<p align="center">
Here you can play the game straight away through itch.io

<p align="center">
  <a href=https://alexrswift.itch.io/ponggame>
    <img src="https://img.shields.io/badge/▶_PLAY-Circular_Pong-brightgreen?style=for-the-badge" alt="Play Button" height="40">
  </a>
</p>
  

<h2> Game Code </h2>




<h3> Reflection </h3>

The main idea I was aiming for when coding my game was a circular pong, in which the
paddles rotate around a fixed circle while the ball bounces between the middle of said
circle. The main Ai tool used was Claude as it is known to be one of the best for coding
games in the industry; as well as the visual studio ai which was noticeably less reliable;
in addition, ChatGPT was used to help me understand and learn the code. Although not
perfect it still provided a solid foundation to build my own code upon while adding
enhanced features.

The enhancements I added were the following:
- An Ai mode where you compete against the unbeatable computer, trying to get
as high a score as you can all while the ball speeds up with every hit. I believed
that a game where you keep playing to beat your high score would give reason to
continue playing.
- The ball has a trail that follows it, adding to the game's aesthetic and separating
it from what would have been a plain game.
- I also added a teal colour to parts of the game, enhancing it further from the
original pong game.
- The circle style of the game is also an enhancement that fundamentally changes
how the game operates. I intended to add more depth to a basic concept as well
as increase the difficulty of the game by increasing the area that the paddle must
cover in order to keep the ball in the arena.
- The final enhancement was the menu, in which you can switch between modes.
I intended to make the game more professional and easier to navigate especially
when adding more than one game mode.

The initial code that Claude provided was good enough to lay a foundation to build up
my code from, however problems started arising when using the Visual Studio ai for
suggestions on the code. It would commonly give false and incorrect code that would
not run in python. One example was when I tried to get help on the balls speed
increasing, the ai would commonly write the error =* instead of what I learnt it to be *=.
Things like this would be common even in the same line it would miss (angle) from the
end of the code, therefore defining the function itself as the variable.
The first mistake that I found was that the scores were swapped, so when one side
scored it would give the point to the opposite side. This was an easy fix as I just had to
swap the code that defined the player in the line of code that changed the score.
I didn't change much of the structure of the original code; however, it may not be
consistent as I only tampered with the code that I wanted to add and that wasn't
working on python.

Python was my choice of script due to its ease of use as well as how readily available
the resources to learn from are. I believed it to be a cleaner script with fewer symbols
than other similar languages like Java, and much faster to code with than MatLab that I
often struggled to learn. The primary reason was due to the Pygame extension which I
believed would give me the best chance to pick up game coding.


---
layout: page
title: Dino Platformer
description: Our take on the classic 2D platformer
img: /assets/img/dino3.png
importance: 2
category: Game Development
---
<iframe width="560" height="315" src="https://www.youtube.com/embed/OtKWK3xuMlM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<div class="caption">
   Dino Platformer: Gameplay Trailer.
</div>
<!-- Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/dino1.png' | relative_url }}" alt="" title="Dino Platformer screens"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/DinoWinScreen.png' | relative_url }}" alt="" title="Dino Platformer screens"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/dino3.png' | relative_url }}" alt="" title="Dino Platformer screens"/>
    </div>
</div>
<div class="caption">
   Dino Platformer: Screenshots!!
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/dino3.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
   Our take on a side scroller platformer which has a Dinosaur as the main character!
</div>

<!-- <b>Tools</b>
<p>C++ 17 for building the Game Engine
SDL2 for abstracting game input and rendering
Javascript for building the Game Level Editor
</p>

<b>Gameplay</b>
<p>The goal of the game is to collect as many coins as you can and reach the red flag! However, you must do this while avoiding enemy characters. If you get hit by an enemy you will lose one life. Be careful you only have 3 lives! To move your character you can use WASD or the arrow keys, with w, up, and space bar being used to jump. To move forward while you jump hit the left/right arrow or A/D as you press spacebar. You can also kill an enemy character by jumping on top of it, however we do not condone violence.
</p>

<b>Special Feature</b>
<p>The special feature in our game is a reverse-parallax! Reverse-Parallax is a scrolling technique in which the background image moves slowly in comparision to the foreground images. This creates an illusion of the game level floating above the background scene.
</p>
<b>Code Architecture</b>
<p>The following docs below are generated through ‘Doxygen’ and gives you an overview of the game code base and architecture of the Game Engine. Architecture Docs
</p> -->
 <div ALIGN=CENTER>
        <h2> Gameplay </h2>
</div>
<p>    
The goal of the game is to collect as many coins as you can and reach the red flag! However, you must do this
while avoiding enemy characters. If you get hit by an enemy you will lose one life. Be careful you only have 3
lives! To move your character you can use WASD or the arrow keys, with w, up, and space bar being used to jump.
To move forward while you jump hit the left/right arrow or A/D as you press spacebar. You can also kill an enemy
character by jumping on top of it, however we do not condone violence.
</p>

<div ALIGN=CENTER>
        <h2> Special Feautre </h2>
</div>
<p>
        The special feature in our game is a reverse-parallax! Reverse-Parallax is a scrolling technique in which the background image
        moves slowly in comparision to the foreground images. This creates an illusion of the game level floating above the background
        scene.
</p>
<div ALIGN=CENTER>
        <h2> Code Architecture </h2>
</div>
<p>
The following docs below are generated through ‘Doxygen’ and gives you an overview of the game code base and
architecture of the Game Engine. <a href="./docs/html/inherits.html"> Architecture Docs </a>
</p>

<div ALIGN=CENTER>
        <h2> Post Mortem </h2>
</div>
<p>Making this game has been a learning process for everyone, if we had more time we could have done a lot more.
</p>
<p>One of our biggest struggles was refactoring the code to use the Component Pattern. We underestimated how long
    and tedious it would be, and that delayed the process of everything else that needed to be done, which left us
    short on time. If we could we would have liked to spend more time fine tuning the physics component. We also
    could have made child classes from game entity like main player, NPCs, collectable item, just to have more
    separation of data types because at the moment we have game entity containing a lot of attributes that may not
    be neccessary for all game entities.
</p>
<p> Besides that it would have been nice if we could have implemented more features. For example having a 2 player
    option or making the character experience different effects from consuming different items like being able to
    temporarily fly after consuming a feather or moving faster after consuming a potion. Another fun idea would have
    been adding a character creator portion of the game where the user can choose different outfits or
    colors for the dino.</p>


<div ALIGN=CENTER>
        <h2> Installing and Running the Game </h2>
</div>
<p><b>Installing the game</b></p>
<p>
        Install the following frameworks
       <li><a href="https://lazyfoo.net/tutorials/SDL/01_hello_SDL/mac/index.php">SDL2</a></li>
        <li> <a href="https://www.libsdl.org/projects/SDL_ttf/"> SDL_ttf </a></li>
        <li> <a href="https://www.libsdl.org/projects/SDL_mixer/">SDL_mixer</a></li>
        <li><a href= "https://www.libsdl.org/projects/SDL_image/">SDL_image</a></li>
        <li>Download and Extract the following ZIP file to a folder. <a href="Game.zip">Game.zip</a></p>
        <li>After Extracting open the terminal and run the following command inside of the Game folder
                <code> python build.py </code></li>
        <li>The above steps would result in binary file being created in the name of <code>Game</code> in the bin folder</li>
       
</p>
    <p><b>Running the game</b></p>
    <p>
        <li>From the root directory type the following command <code>./bin/game</code></li>
    </p>
    <p>Entire Project including Documentation: <a href="Game.zip">download project files</a></p>
    <p>Binary for Mac OS: <a href="bin/game">download binary file</a> </p>





<!-- You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal it's glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/6.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/" target="_blank">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/6.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
``` -->

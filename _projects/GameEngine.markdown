---
layout: page
title: Platformer Game Engine 
description: Game Engine built using SDL2 and C++
img: /assets/img/GameEngineMenu.png
importance: 1
category: Game Development
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/GameEngineMenu.png' | relative_url }}" alt="" title="Main menu of our engine"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/tile_maker.png' | relative_url }}" alt="" title="Tile Map maker"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/sprite_tool.png' | relative_url }}" alt="" title="Sprite Previewer"/>
    </div>
</div>
<div class="caption">
  Too Busy Engine: Main Menu, Tile Map maker and Sprite Previewer
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/galaga.png' | relative_url }}" alt="" title="Galaga"/>
    </div>
</div>
<div class="caption">
Galaga developed using our Engine!
</div>


<div ALIGN=CENTER>
        <h2>Trailer</h2>
</div>
<div ALIGN=CENTER>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/bDl127Ng1_k" title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen></iframe>
</div>


<div ALIGN=CENTER>
        <h2>Engine Abilities</h2>
</div>
<p>
        With this engine you can write a game in Python. SDL2 features are used in C++ functions that are exposed
        via
        Pybind11. We have recreated the game Galaga in python, but other games can be created as well! There is also
        a
        tile map editor you can use to create your own tile map, by putting in the complete file path of an image
        you
        want to use and the tile map dimensions you want. You can also preview sprite animations, by using the
        sprite
        animation tool and putting in the complete file path of the image you want to use, how big you want the
        sprite
        to be, and the start and end frame number.
</p>
<div ALIGN=CENTER>
        <h2>Wow Factor</h2>
</div>
<p>
        We wanted our game engine to be extensible, therefore we used Entity component system as the foundation of our
        engine. ECS follows the composition over inheritance principle that allows greater flexibility in defining
        entities where every object in a game's scene is an entity (e.g. enemies, bullets, vehicles, etc.). Every entity
        consists of one or more components which contains data or state. Therefore, the behavior of an entity can be
        changed at runtime by systems that add, remove or mutate components. This also helped enable use to create a
        variety of games using our engine, so you could make a platformer using our engine, it could be top down or
        bottom up, or you can make an arcade game like Galaga.
</p>
<div ALIGN=CENTER>
    <h2>Galaga</h2>
</div>
<p>
    In order to move the spaceship use A and D, and to shoot your enemies use spacebar. You can quit the game by
    pressing Q. You have 3 lives so be careful! There are no levels, but as time goes on the game gets more
    challenging.
</p>

<div ALIGN=CENTER>
    <h2> Post Mortem </h2>
</div>
<p> 
A project like a game engine is never fully completed. If there was more time there are many things we would
    have like to try to implement. We would have liked to try to optimize our collision handling system, perhaps
    by
    implement a broad phase and narrow phase system. Also we could have exposed more SDL2 features to python, so
    users creating their game in python could have more creative control when developing the game.
</p>
<p>
We would have also liked to add other tools. It would have been nice if we could have created a paint like
    tool
    that users could use to create their own background images and characters, instead of making it on another
    platform and saving it and loading it from there. Another tool that would have been useful is a simulation
    tool
    used to view how collisions are handled.
</p>

<div ALIGN=CENTER>
    <h2> Class Hierarchy </h2>
    <div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/diagram1.png' | relative_url }}" alt="" title="Class Hierarchy"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/diagram2.png' | relative_url }}" alt="" title="Class Hierarchy "/>
    </div>

</div>
    
</div>



<div ALIGN=CENTER>
    <h2> Project Files, Binaries, & Documentation </h2>
</div>
<p>The following libraries are needed in order to run the game: Tkinter, PyQT, Pybind11, SDL2, SDL_Mixer,
    SDL_ttf,
    and
    SDL_image.
</p>
<p>Run the following in order to build the executable <code> python build.py</code>. After you can run the
    following to start the engine and play a game, use the sprite tool, and tile map tool.
    <code> ./bin/start</code> .</p>
<p>Entire Project: <a href="Engine.zip">download project files</a></p>
<p>Binary for Mac OS: <a href="bin/start">download binary file</a> </p>
<p>Documentation: <a href="docs.zip">download doxygen generated files</a> </p>


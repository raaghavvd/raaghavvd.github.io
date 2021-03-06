---
layout: page
title: Breakout
description: A recreation of a classic game
img: /assets/img/Breakout_Image.jpg

importance: 1
category: Game Development
---
<!-- 
Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    --- -->
Breakout was one of the games which laid the foundations for my interest in video games. Therefore, this homework was an absolute blast for me.
Given that I have worked for more than a week for the game and I’m pretty happy with the finished product and if I had 6–8 weeks to work on it, I would have done more things and fixed some bugs. Below is the trailer of the game.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/Breakout_Win.png' | relative_url }}" alt="" title="Breakout Win Screen"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/BreakOut_Lost.png' | relative_url }}" alt="" title="Breakout Lost Screen"/>
    </div>
    <!-- <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/5.jpg' | relative_url }}" alt="" title="example image"/>
    </div> -->
</div>
<div class="caption">
   Few Screenshots from the game.
</div>
Early draft of the game and how the home screen would look like if created</div>
Ideally, I would’ve liked a start screen, which allowed the user to pick the language they want and allow them to start the game, I think this is a more interactive option and certainly more appealing for the user.
Additionally an option to pause the game would also be good, the current build is literally akin to playing the game in an arcade game parlour.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/design_breakout.png' | relative_url }}" alt="" title="Early Design image"/>
    </div>
     <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/-breakout_home.png' | relative_url }}" alt="" title="Home Screen Visualized"/>
    </div>
</div>
<div class="caption">
Early draft of the game and how the home screen would look like if created</div>
Ideally, I would’ve liked a start screen, which allowed the user to pick the language they want and allow them to start the game, I think this is a more interactive option and certainly more appealing for the user.
Additionally an option to pause the game would also be good, the current build is literally akin to playing the game in an arcade game parlour.

I certainly would like to improve the aesthetics of the game, adding blocks in between the bricks would be good, this would make the collisions with the ball a bit more unpredictable, which brings me to the point of using randomized velocities, which would be influenced by an angle, according to the position the ball collides at. This would also help making the forthcoming levels harder. We don’t want the game to be too easy, so certain special bricks could be created, which could give the ball a special power, this could be becoming a fireball, which makes the bricks destroyed at one hit, rather than two hits. This power would remain for a given amount of time and the ball would to back to its normal state after that. Similar thing could be implemented for a paddle.
I would also clean up the code and test the game. Game testing is very crucial to building a really good game, ofcourse one can’t find all the bugs, but finding enough helps to make the user experience smooth and also allows to spread the good word. The below is a link to the public git repo which contains the build and the documentation.

Below is the trailer of the game.


<iframe width="560" height="315" src="https://www.youtube.com/embed/WKMdNbbo05w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>





To conclude, this was an excellent experience for me and I learnt a lot in my game dev journey with SDL and C++.


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

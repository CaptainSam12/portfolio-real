---
toc: true
layout: post
title: Night at the Museum Blog
description: What I saw at Night at the Museum (N@TM) 2026!
tools: Github Cloning, Virtual Environments, and Running a local website.
permalink: /blog/nightatthemuseum
---

Overall
---
Night at the Museum is a really great event where you can see what all of your peers have created. As a freshman, this was super cool and important to see because it influenced my choice on what electives and classes to choose throughout my years at Del Norte

CS Classroom
---
I will admit, I have been super curious to see what the other students in CSP and CSA have been doing. Our TA is a very talented person who completed both of these courses, so I wanted to see what my life in the classroom would be if I took those courses. Needless to say, I wish I took a billion more pictures because my camera roll does not support what I saw!

<style>
    /* Style looks pretty compact, 
       - grid-container and grid-item are referenced the code 
    */
    .grid-container {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); /* Dynamic columns */
        gap: 10px;
    }
    .grid-item {
        text-align: center;
    }
    .grid-item img {
        width: 100%;
        height: 100px; /* Fixed height for uniformity */
        object-fit: contain; /* Ensure the image fits within the fixed height */
    }
    .grid-item p {
        margin: 5px 0; /* Add some margin for spacing */
    }

    .image-gallery {
        display: flex;
        flex-wrap: nowrap;
        overflow-x: auto;
        gap: 10px;
        }

    .image-gallery img {
        max-height: 150px;
        object-fit: cover;
        border-radius: 5px;
    }
</style>

<!-- This grid_container class is used by CSS styling and the id is used by JavaScript connection -->
<div class="grid-container" id="grid_container">
    <!-- content will be added here by JavaScript -->
</div>

<comment>
Gallery of Pics, scroll to the right for more ...
</comment>
<div class="image-gallery">
  <img src="{{site.baseurl}}/images/A_CSP_Game_Teaching_Crypto.jpg" alt="Crypto Game ">
  <img src="{{site.baseurl}}/images/A_CSP_Multiplayer_Game.jpg" alt="CSP teaching a multiplayer game">
  <img src="{{site.baseurl}}/images/Our-Game.jpeg" alt="Image 4">
  <img src="{{site.baseurl}}/images/AI-Prompting-CSP.jpg" alt="Imae 5">
  <img src="{{site.baseurl}}/images/Computer.jpeg" alt="Image 6">
  <img src="{{site.baseurl}}/images/Our-class.jpg" alt="Image 7">
  <img src="{{site.baseurl}}/images/Our-game-2.jpg" alt="Image 8">
  <img src="{{site.baseurl}}/images/natm5.jpg" alt="Image 9">
  <img src="{{site.baseurl}}/images/NATM10.jpg" alt="Image 10">
</div>

Let me explain these pictures:
1: A CSP game teaching crypto.

2: A CSP multiplayer game.

3: Our class's game (This picture is actually of our level, level 2) I will link the game down at the bottom! (Under the picture of artwork)

4: A CSP Project about AI prompting

5: The gamebuilder that we used to build our game!

6: The people from our class that presented our game.

7: Another one of our levels (The blue screen) 

8: This is a platform called Hunger Heroes:

Hunger Heroes is a platform designed to connect people who want to give with those who need support, creating a direct and efficient pathway between donors and recipients. While exploring how it works, I discovered that the developers built it with a solid technical backbone: a backend database to handle user accounts and an API integration that powers the map features.

10: This site works like a vacation‑planning game, turning trip organization into something fun instead of stressful. While digging into how it was built, I found out the developers integrated several APIs — one to pull in landmarks, another for shopping spots, and even one that fetches live weather data. It’s a surprisingly clever mix of tech behind a playful interface.

You can tell which presentations I listened to the most! The Vacation game and Hunger Heroes were the most eyecatching due to their amazing craftmanship and the wonderful design.

Outside of CS
---
Outside of the CS classrooms, I found a lot more things, there was art, photography, pottery. A walkthrough type gallery. The students were all very passionate to share their work, and they all offered good advice and help for future endeavors. 

<img src="{{site.baseurl}}/images/NATMART.png" style="height:500px; margin-right:250px;">

Link to our Murder Mystery Game!

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
    <a href="https://pages.opencodingsociety.com/gamify/murderMystery" style="text-decoration: none;">
        <div style="background-color: #ac2308; color: black; padding: 10px 20px; border-radius: 5px; font-weight: bold;">
            Murder Mystery Game
        </div>
    </a>

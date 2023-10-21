---
title: "Open Positions"
permalink: /docs/open-positions/
excerpt: "Instructions for installing the theme for new and existing Jekyll based sites."
last_modified_at: 2023-10-20T21:36:18-04:00
toc: true
---

<style>
input
{
 background: #252a34 !important;
},
form
{
display: block;
},
select
{
background-color: #252a34;
display: block;
},
br
{
display: block !important;
},
</style>


## Coders

**Looking for**:

- A Good C# coder.
  We have chosen what we believe to be a good engine for the project.
   
  - Open Source Engine
  - Written in C# (.NET6) Possibly .NET8 soon
  - Scripting in C# 10
  - OOB compatibility with most C#/.NET Libs

**Status**: Open 🟢


## Artists

- 3D Artist
 Characters & Weapons
  - "Medium Poly"
     Higher than "Polygon"  Less than: AAA Games like COD.
  - Animation skill a plus
  - I'm leaning to a more arcade art style like
    - Fortnite
    - Apex Legends
    - Overwatch
    - DOTA 2

**Status**: Open 🟢

  We will go different directions here and there, but this is a starting point.  Some people call this "Stylized Fantasy" some call it "Hand Panted" the terms are subjective.  but the general rule we want to follow is slightly cartoon-ish textures but not overly.. simply put a good balance between realism and stylized


## Overview

**Our talent**: Well I'm currently the only team member, the less members required to accomplish the project means more revshare. That said, I'm a jack of all trades,  i can do some

- Some 3D modeling
- Some Coding
- Some Level design  
  
I've also been collecting both free and paid 3D assets for years I think i have like 20GB of them at this point.  some may be useful some may need a reskin some might not work for the art style.

**Project**: The project is highly ambitus which may be overwhelming to some, I personally subscribe to a go big or go home mentality.  The game is FPS, it's just what I know and what holds my interest even if its over-done.  It's the concept I understand the best.  

*Currently implemented:*

- Engine Chosen
- Art-style loosely chosen.
- We are using GIT for VCS, the project structure of our engine lends itself well to being versioned in fact, our basic project with a handful of assets our repo is only ~130MB I've seen some engines take 3x that just to create a project.
- *Note* the repo isn't on a public service yet I maintain an internal repo, that i will push to either Github or Gitlab  i haven't decided yet which one is going to fit best probably Github for better LFS support.
  
*Future work*:

- One of the downsides of the engine is we will somewhat need to roll our own netcode/multiplayer. However there are some existing code examples available for that we are evaluating. and since we can easily drop in almost any C# library without the engine complaining too much the sky is kinda the limit.
- A lot of discussion on the best ways to design the project for example.

  - FPSArms vs FullBody ?? each have their challenges in multiplayer
  - Bullet (Projectile) Physics
    - RayCast is cheap but gets complicated when you need bullet drop
    - Rigidbody Projectiles are more accurate but have to be managed in multiplayer so you don't end up with 100k entities.
  - Repeatable texture skins
    - Weapons
    - Characters

**Theme**: The game theme is very much in flux we should probably get basic functionality working before designing them theme too much.. but the two ideas I've personally tossed around are

- Modern Day Civil War
- AI vs Human war

Length of project: Actual development? not that much I've spent most of the last few years learning game engines and the basic concepts. But I've been brainstorming the project for about 5 years.  as for how long it would take to complete that depends on how many team members we end up with.  

**Split**: 15%  - Subject to change.

- The term rev-share implies before expenses. Considering Steam takes 30% off the top when we release there. We have to consider the business expenses of distribution because we intend to self-publish.

- Please also note, that we would welcome hobbyist team members, we want to make clear this is not a position where we are going to be demanding output from you, first and foremost we want to learn together how to accomplish the hard parts..

- The one thing we will likely ask is that anyone that contributes to the project sign a release on the assets (code or art) they make for us just so we are covered to use them legally. It's difficult to negotiate compensation for one off works for example, is it fair to give a total rev-share on a single asset? we're not sure, it's open for a discussion at least.

## To Apply


<div>
<form style="display: block:" action="https://getform.io/f/b537e434-214c-4d39-9254-bba4aaf26766" method="POST">
    Name:
	<input type="text" name="name">
    Email:
	<input type="email" name="email">
    Describe your skill:
	<textarea cols="40" rows="5" name="message"></textarea>
    <!-- add hidden Honeypot input to prevent spams -->
    <input type="hidden" name="_gotcha" style="display:none !important">
<br>
<br>
	<!--Position -->
	Position:
<br>
	<input type="checkbox"> 3D Artist
<br>
	<input type="checkbox"> Coder
<br>
<br>
    <!-- radio button handle -->
    <input type="radio" name="gender" value="male" checked> Male
<br>
    <input type="radio" name="gender" value="female"> Female
<br>
    <input type="radio" name="gender" value="other"> Other?
<br>
<br>
    <!-- select field handle -->
Work Experiance
   <select name="work-experience">
    <option value="one-year">0-1 years</option>
    <option value="one-three-years">1-3 years</option>
    <option value="three-six-years">3-6 years</option>
   	<option value="The-Hammer-Of-Thor">GODLIKE!</option>
   </select>
<br>
    <button type="submit">Send</button>
</form>
</div>
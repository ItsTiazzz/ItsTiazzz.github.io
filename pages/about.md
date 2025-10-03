---
layout: page
title: About
permalink: /about/
weight: 1
---

# **About Me**

Hi I am **{{ site.author.name }}**,  
I'm an amateur developer, and currently a student in the Netherlands.

I like making Open Source projects, and learning new things. Mostly interested in Discord bots and 
Minecraft mods though.
{% include elements/button.html link="../projects" text="Check out all my projects" block=true %}

Oh also, I work for CordCraft as a developer and head of administration!
{% include elements/button.html link="../r/cc-discord" text="Join our Discord server here" block=true %}

Alongside this, I did some contributions to some projects in form of translations for my native language, Dutch.
{% include elements/button.html link="../translation-projects" text="Check those out here :3" block=true %}

Oh, also I kinda pulled the following values out of my ass, but they're like more or less correct in terms of hierarchy...

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
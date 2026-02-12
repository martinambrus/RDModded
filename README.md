⚠️ Effort moved to Fabric-enabled RubyDung
------------------------------------------
Go to **[RDForward](https://github.com/martinambrus/RDForward)** if modding a nearly 20-years old game (in 2026) is your niche :-{}

----------

RubyDung 2009 Modded
--------------------
This is a crazy experiment from some crazy people aiming at the creation 
of an early mods-enabled Minecraft versions, starting as early as its 2009 inception, 
when Minecraft was still called *RubyDung*.

Also, this is a learning project for me. I've never seen how a Java game is made, 
so naturally decompiling Notch's old code should teach me something new and cool... right?
 :-D

![A modded RubyDung version with chocolate blocks instead of cobblestone and grass](https://i.imgur.com/0SsXWWt.png "A modded RubyDung version with chocolate blocks instead of cobblestone and grass")

Downloads
---------
Due to copyright limitations, the only kind of direct download would be available as a result 
of [automated GitHub Build Actions](https://github.com/martinambrus/RDModded/actions) 
(even so, I'm not quite sure that this is kosher, so we shall see). That said, it's super-trivial 
to build this project on your own by just downloading the Java IDE and running 2 tasks in there (see below).

Building
--------
This repository contains all the tools necessary to build an augmented RubyDung version 
that is prepared for accepting 3rd party mods. Here are the steps:

1) install [gradle](https://gradle.org/) (v8.5 is tested) - or better yet, get the free Java development IDE [IntelliJ Idea](https://gradle.org/)
2) run two gradle tasks:
   1) *first_time_run*
   2) *shadowJar*

This will generate a RubyDung mods-enabled version which you can run via [MultiMC](https://multimc.org/) 
and create your very own mods for.

Creating Mods
-------------
There is a sample [Time Slower mod](https://github.com/martinambrus/RDModTimeSlower) 
to get you started. The actual [API](https://github.com/martinambrus/RDApi) 
is fairly simple and if you ever saw a [Bukkit API](https://hub.spigotmc.org/javadocs/bukkit/) 
or coded for [Spigot](https://www.spigotmc.org/wiki/spigot-plugin-development/) / 
[Paper](https://www.spigotmc.org/wiki/spigot-plugin-development/) / 
[Purpur](https://purpurmc.org/) in your life, this should feel familiar.

Documentation
-------------
Once there is a stable first version of the API, documentation will follow. I'm pretty big 
on documenting things, so the documentation will definitely be there and up-to-date.

More Resources
--------------
You may want to check the [Minecraft Veteran Servers YouTube Channel](https://www.youtube.com/channel/UCMiKrpX4ViX4PGBOq1UXlvQ) for videos on creation of all this nonsense and perhaps some inspiration for creation of your own game / Minecraft clone :-D

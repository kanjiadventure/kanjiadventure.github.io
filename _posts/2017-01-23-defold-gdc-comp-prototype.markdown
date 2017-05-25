---
layout: post
title:  "Defold GDC competition prototype"
date:   2017-01-23 17:59:00 +0200
categories: kanjiadventure
---
Now that the initial release is out of the bag, I would like to share what we intend to do in the not so distant future in regards to battle system and talk about how the idea for the game came into fruition.

![Prototype screenshot 1](/assets/images/gdc1.jpg)
![Prototype screenshot 2](/assets/images/gdc2.jpg)

# The idea

I have first thought about creating a game in December 2015, when I was studying abroad in Japan. Each week we would receive kanji characters that we had to learn on multiple sheets of paper, an experience which turned out to be pretty boring and at the same time not very effective. I have had prior experience with applications for spaced repetition such as Memrise and Anki and while they were terrific for vocabulary learning, I struggled with using them for learning kanji for various reasons.

![Old-school paper-based learning approach](/assets/images/idea.jpg)

Dissatisfied with current offerings I sat down one evening and created a [very simple web application][kanjiapp] that tests the user. Then I had an epiphany - wouldn't it be cool to make this into what is arguably the most engrossing media format known to man - a video game? I knew that if I were to do this I wouldn't be satisfied with a simple gameplay mechanic or gamification element, I wanted something that feels like a traditional video game and would attract as broad an audience as possible, including more hardcore brethen, while at the same time not alienating casual players.

I have searched for a perfect game genre to incorporate the learning mechanic into and I believe I found it - a turn-based RPG that draws inspiration from games such as Fire Emblem, Final Fantasy Tactics or Dofus. I have spent better part of 2016 coming up with design decisions and looking up books on game design (and yes, I know that choosing the RPG genre for your first title is an awful decision :) and started 2017 by creating the battle prototype that you can download below. I shouldn't forget to name my comrade in arms who is good at stuff that I am terrible at - namely non-trivial graphical design - David, a friend from high school who I am tremendously grateful to be working alongside with. Thanks, Dave!

# Short roadmap

* **Better Animations** - the current animations are, for the most part, placeholders and have been designed to be implemented as quickly as possible. Unfortunately, creating animations in isometric perspective has proven to be pretty time-consuming for Dave, so we weren't able to include them with our initial build.
* **Challenges** - the player will be given an objective to solve during the battle in exchange for virtual currency, loot, etc., further down the road we intend to integrate this system into overworld quests
* **Obstacles** - these will limit where the player can cast spells as well as add visual flair to the game
* **Battle Tutorial** - the current tutorial system is fairly basic, therefore we intend to create a series of dialogs

![Our aim](/assets/images/aim.jpg)

# Long-term goals

* **A full living world** - I want the overworld to be sufficiently large and to include quests that will lead the player throughout the experience and keep him/her motivated, it is of paramount importance to keep player's motivation high and in the best case scenario to keep him playing every day as to reap the educational benefits
* **Adaptive learning system** - I believe that the back-end for our learning system should be as strong as the game mechanics themselves. The finished product will utilise a modified [Leitner system][leitner] which will introduce statistical bias to kanji depending on correctness of player's answers. Tough kanji will show up more frequently in queries.

[Here is the initial build][build]

Hope you will enjoy playing the builds as much as we have enjoyed making them. Stay tuned! :)

[build]: https://github.com/Tomires/kanjiadventure_release/releases/tag/gdc_comp
[kanjiapp]: http://j3.kanji.tomires.eu/
[leitner]: https://en.wikipedia.org/wiki/Leitner_system

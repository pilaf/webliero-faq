<p align="center"><img src="wl-faq-logo.svg" width="300"></p>

This is meant as a community-updated FAQ for [WebLiero](https://www.webliero.com).

To add a question create an issue or submit a pull request (all you need to know is Markdown syntax).

## Index

* [General](#general)
  * [How is WebLiero different from the original DOS Liero?](#how-is-webliero-different-from-the-original-dos-liero)
  * [Does WebLiero support loading custom Liero maps?](#does-webliero-support-loading-custom-liero-maps)
  * [How can create my own maps or edit existing ones?](how-can-create-my-own-maps-or-edit-existing-ones)
  * [Does WebLiero have bots?](#does-webliero-have-bots)
* [Game modes](#game-modes)
  * [What game modes does WebLiero support?](#what-game-modes-does-webliero-support)
* [Room List](#room-list)
  * [What are rooms with DED in their name?](#what-are-rooms-with-ded-in-their-name)
* [Mods](#mods)
  * [Does WebLiero support loading custom mods](#does-webliero-support-loading-mods)
  * [Can WebLiero load original LIERO.EXE mods?](#can-webliero-load-original-lieroexe-mods)

## General

### How is WebLiero different from the original DOS Liero?

Besides the obvious differences (like the fact that it's played in a browser and has online-multiplayer), here are some other differences:

* Worms have no shadows
* The random map generator uses a different (improved) terrain generation algorithm
* Maps can be mirrored to allow double the play area
* *(this list is incomplete, help me complete it)*

### Does WebLiero support loading custom Liero maps?

Yes. If you're the host of a room you can load maps in .lev format from the Admin menu.

### How can create my own maps or edit existing ones?

Check the [liero-palettes](https://github.com/pilaf/liero-palettes) GitHub repo, which contains a guide on how to edit Liero maps using available free software.

### Does WebLiero have bots?

No. Every player you see is a real human.

## Game modes

### What game modes does WebLiero support?

Dathmatch, Hold the Flag, Last Man Standing and Team Deathmatch.

#### Deathmatch

Classic free-for-all skirmish. The first player to reach the score limit, or the player with the highest score when the clock reaches 0:00 wins the match.

#### Hold the Flag

A flag is dropped somewhere in the map. Holding it scores you 1 point for each second that goes by. The first player to reach score limit &times; 10, or the player with the highest score when the clock reaches 0:00 wins the match.

#### Last Man Standing

Players have a limited amount of lives. Losing all lives forces you into spectator mode until the match endes. The amount of lives players enter the game with is determined by the room's score limit, although players entering an in-progress game may have their initial lives capped for fairness. The last player to stay alive, or the player with the most lives left when the clock reaches 0:00 wins the match.

#### Team Deathmatch

Players pick one of two teams. Every death counts as a point for the other team, even if it's a suicide or a self-team-kill. The first team to reach the score limit, or the team with the highest score when the clock reaches 0:00 wins the match.

## Room List

### What are rooms with DED in their name?

DED stands for *dedicated*. Those are rooms hosted by dedicated servers and are on 24-7. Since they're on dedicated servers they tend to have good network reliability (i.e. low lag).

## Mods

### Does WebLiero support loading custom mods?

Yes. You can load mods by entering the `/loadmod` command in the chat.

### Can WebLiero load original LIERO.EXE mods?

No. WebLiero uses its own mod format. Eventually there may be tools to convert from original LIERO.EXE mods to WebLiero mods.

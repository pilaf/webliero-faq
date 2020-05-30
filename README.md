<p align="center"><img src="wl-faq-logo.svg" width="300"></p>

This is meant as a community-updated FAQ for [WebLiero](https://www.webliero.com).

To add a question create an issue or submit a pull request (all you need to know is Markdown syntax).

## Index

* [General](#general)
  * [How is WebLiero different from the original MS-DOS Liero?](#how-is-webliero-different-from-the-original-ms-dos-liero)
  * [Does WebLiero support loading custom Liero maps?](#does-webliero-support-loading-custom-liero-maps)
  * [How can I create my own maps or edit existing ones?](#how-can-i-create-my-own-maps-or-edit-existing-ones)
  * [Does WebLiero support Gusanos/LieroX/OpenLieroX maps or mods?](#does-webliero-support-gusanoslieroxopenlierox-maps-andor-mods)
  * [Does WebLiero have bots?](#does-webliero-have-bots)
* [How to play](#how-to-play)
  * [What are the default WebLiero controls?](#what-are-the-default-webliero-controls)
  * [What are some popular alternative control schemes?](#what-are-some-popular-alternative-control-schemes)
  * [What are some lesser known tips on Liero controls?](#what-are-some-lesser-known-tips-on-liero-controls)
* [Game modes](#game-modes)
  * [What game modes does WebLiero support?](#what-game-modes-does-webliero-support)
* [Room List](#room-list)
  * [What are rooms with DED in their name?](#what-are-rooms-with-ded-in-their-name)
* [Mods](#mods)
  * [Does WebLiero support loading custom mods](#does-webliero-support-loading-mods)
  * [Can WebLiero load original LIERO.EXE mods?](#can-webliero-load-original-lieroexe-mods)
  * [How can I make my own mods?](#how-can-i-make-my-own-mods)
  * [What can mods change in the game?](#what-can-mods-change-in-the-game)
* [Community](#community)
  * [Where can I interact with the WebLiero community?](#where-can-i-interact-with-the-webliero-community)
  * [What are other websites related to WebLiero?](#what-are-other-websites-related-to-webliero)

## General

### How is WebLiero different from the original MS-DOS Liero?

Besides the obvious differences (like the fact that it's played in a browser and has online-multiplayer), here are some other differences:

* The random map generator uses a different (improved) terrain generation algorithm
* Maps can be mirrored to allow double the play area
* *(this list is incomplete and/or outdated, help me complete it by opening an issue)*

### Does WebLiero support loading custom Liero maps?

Yes. If you're the host of a room you can load maps in .lev format from the Admin menu.

### How can I create my own maps or edit existing ones?

Check the [pilaf/liero-palettes](https://github.com/pilaf/liero-palettes) GitHub repo, which contains a guide on how to edit Liero maps using available free software.

### Does WebLiero support Gusanos/LieroX/OpenLieroX maps and/or mods?

No. WebLiero is based on the original MS-DOS Liero, and thus is only compatible with content for that game.

### Does WebLiero have bots?

No. Every player you see is a real human.

## How to play

### What are the default WebLiero controls?

<p><img src="keyboard-layout.svg"></p>

The default control scheme is:

* Left/Right arrows to move
* Up/down arrows to aim
* A/S/D are your default keys to shoot, jump, and show weapon, respectively
* Press show weapon + arrow (left or right) to switch weapons
* Press show weapon + jump to shoot the ninja rope
* To dig through dirt, tap C, or alternatively, hold the forward arrow key while tapping backward arrow

Additional keys:

* Hold the tab key to view the player scores
* Press enter to open the chat window

### What are some popular alternative control schemes?

While you should tinker with the control scheme on your own to see what works best for you, here's an alternative for you to try that some players are known to use:

* W/A/S/D for movement/aim
* F/G/H for shoot, jump, and show weapon, respectively
* Q/E for quick weapon change
* R for weapon reload (this  has no default key binding)

### What are some lesser known tips on Liero controls?

* You can shorten/lengthen the ninja rope by holding the show weapon key and pressing up/down
* You can make missiles go faster by pressing the up key
* On steeply sloped surfaces (i.e. ramps) you can quickly gain vertical speed by repeatedly tapping the jump key while walking towards the ramp

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

Yes. You can load mods by entering the `/loadmod` command in the chat and selecting both the mod.json5 and sprites.wlsprt files.

### Can WebLiero load original LIERO.EXE mods?

No. WebLiero uses its own mod format. Eventually there may be tools to convert from original LIERO.EXE mods to WebLiero mods.

### How can I make my own mods?

While you can, and are definitely welcome to create WebLiero mods, be warned that the mod format for WebLiero is not fully "solidified" yet. In other words, mods you create today may become incompatible and require updating as new versions of WebLiero get released. Once the developer of WebLiero settles on a final mod format this warning may become obsolete, but there are no guarantees.

That said, [Scharnvirk's WebLiero mods GitHub repo](https://github.com/Scharnvirk/webliero_mods) is a good place to start if you want to mod WebLiero. There's no official documentation yet, but you can tinker with the mods in that repo and try to figure out how things work on your own (it's not very difficult).

If you have questions you can ask in the community [Discord](#where-can-i-interact-with-the-webliero-community).

As WebLiero matures better tooling for editing mods may appear.

### What can mods change in the game?

While mods can radically change how the game looks and feels, they are limited in what they can do. Mods can change the game's color palette, game sprites (i.e. the art for worms and particles), weapons, and some game physics properties (i.e. gravity, movement speed, etc.). Mods *cannot* be scripted however, meaning any changes to the game outside of the aforementioned list is outside their scope (i.e. you can't add game modes or change the core game logic through mods).

While that may sound limiting, through creative use of the weapon/particle system, creating innovative mods is still very much possible.

## Community

### Where can I interact with the WebLiero community?

For English language discussions about WebLiero you can join the [Liero Discord server](https://discord.gg/UmmtcA6), or the [/r/liero](https://reddit.com/r/liero) subreddit. Both are for general Liero discussion (i.e. not just WebLiero), but WebLiero being the most actively played Liero clone it's the main topic of discussion in both forums.

For Polish language you may check out the original [Liga Liero Forums](https://www.liero.org.pl/).

There may be discussions forums in other languages, if you know of any please open an issue to have it added here.

### What are other websites related to WebLiero?

* [Liero.be](http://liero.be/) is the official Liero website. There you can find downloadable versions of the original Liero, as well as information on the history of Liero and news about the game.
* [Liero Hell Hole](http://www.liero.nl/) is the biggest archive of original Liero content, especially maps (most of which work with WebLiero). The website has been running since the early 2000s, so it's a bit outdated in terms of web design, but it's an invaluable resource for the Liero community.

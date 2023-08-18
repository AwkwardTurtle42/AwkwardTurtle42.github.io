---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Home
nav_order: 1
---

# DEVELOPMENT BRANCH - THIS SRD IS A WORK IN PROGRESS AND INCOMPLETE. 

[![Brighter Worlds](TitleImage.png "Brighter Worlds RPG")](https://awkwardturtle.itch.io/brighter-worlds)

Expect unedited text, typos, and missing hyperlinks. If you're looking for the current stable version go [here](https://brighterworldsrpg.com/).

**Brighter Worlds** is a whimsical fantasy tabletop RPG with modular crunch.

Writing & Layout by David Lombardo ([AwkwardTurtle Games](https://awkwrdturtle.games))

A fully illustrated PDF, featuring [Evlyn Moreau](https://www.patreon.com/evlynmoreau)'s artwork, is available [free on itch.io](https://awkwardturtle.itch.io/brighter-worlds). This PDF is **not** currently at version parity with this SRD, instead it matches the [live site's alpha version 0.9.3](https://brighterworldsrpg.com/).

It is unfinished, currently at Beta Version 0.1, but approaching feature completeness.

Brighter World’s text is licensed under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

Rules based on Into the Odd by Chris McDowall ([www.bastionland.com](https://www.bastionland.com/)), Cairn by Yochai Gal ([cairnrpg.com](https://cairnrpg.com/)), and Macchiato Monsters by Eric Nieudan ([@surcapitaine](https://twitter.com/surcapitaine)).

## Recent changes

* Additions (current and planned)
    * Unfinished Business is a small "dungeon" adventure intended to be an introduction to the playstyle and tone of Brighter Worlds.
    * Example of Play running through said adventure still a WIP but will be added soon.
    * Players now start with Coins, and there *will soon* be an actual price list/cost guideline included.
    * Pre-Gens, which I'm counting as an addition because I'm scrapping all current ones and starting over.

* Changes
    * Grit is now derived from DEX and WIL. Grit starts at 1 and goes up by one each time Max DEX or WIL is stepped up. This is intended to serve multiple purposes.
        * This should help "balance" the importance of the Attributes, as previously STR was far and away the most important in terms of suitability. I'm not hugely fussed with overall balance, but I didn't want there to be an obvious correct choice.
        * It makes conversions somewhat easier since you can just set the Attributes and already have Grit generated.
        * Removing the ability to spend XP directly on Grit makes the "when you spend XP" ability triggers in some Callings work more smoothly.
        * Starting Grit is now 2-4 which is where I want it, and the "default stats" generic NPC cleanly works out to 3 Grit with d6 in all Attributes.
    * Callings that used Grit as a resource (Runewright and Crystal Wizard especially) have been changed to no longer do so. This is to avoid potential optimization issues at character creation.
    * All the various extraneous extra bits I've added to character creation in various versions have been removed (1 XP, one advanced ability, etc). 
        * It was all just too much extra fussing in my playtests. It didn't add much and dramatically increased how much reading was needed and how much time was spent making decisions before we could start playing.
        * The Starting Equipment tables have been truncated to 8 entries as a result of this, since there's no way to foll d10's on them anymore.
    * All Callings have been reformatted. Previously there was some inconsistency as to what information showed up in "Core Ability" vs the section that expanded on rules.
        * Now every Callings starts with "You Are A..." which includes a summary and any required character creation instructions.
        * This is followed by a Core Ability section that has all rules related to their core ability.
        * A number of Callings have been tweaked and cleaned up during this process, but I won't list all the changes.
    * Significant Calling Updates
        * There are a number of minor changes scattered around that I'm not going to fully list out.
        * Sneaky Bastard was changed to make the different clone types feel more unique and interesting, and most importantly the Shadow Clone was changed to have more limitations.
            * I'd received feedback that it was the ultimate scout, but didn't fully appreciate to what extent until I had it at my own table. I'm not even bothered by how its potentially too powerful, it's just *very annoying* for the GM to need to rapid fire explain the layout of every room in a dungeon + enemies + mucks up wandering monster rolls and such. This is the same reason that the Bone Sense ritual was removed.
            * The new version hopefully retains the fun and interesting things you can do the ability, but limits the "out of scope" information pressure it puts on the GM.
        * Soulbearer now has the Psychopomp ability as part of its core ability. 
            * Honestly that's the most fun part of that calling, and I think people looking to play a druid style transforming character would feel limited when told they could only do *one* animal form.
            * The new Advanced Ability created to replace it allows the Soulbearer to manifest a carried soul physically outside of themselves.
        * Runewright now has Keyrunes on their body which are used to activate their Runes.
            * This is primarily to avoid remove the use of Max Grit which happened previously. This was already annoying at the table, and I was looking for a way to replace this, so it was all copacetic.
            * Clarified how carving and activing runes works.
            * Replaced one Advanced Ability to give more flexibility with creating triggers and remote activation.
        * Cleric of Small Gods now just *enhances* or *impairs* the Domain Die, rather than freely stepping up and down.
            * I found it a bit annoying at the table to go through the process each time a player wanted to use their ability. This way it leans on the already used mechanic of roll modifiers and makes it easier for the GM to make a quick ruling.
    * The Wilderness Survival rules have been dramatically changed.
        * Honestly these might be overkill for this game, might just ditch the entire section in the future.
        * The issue I'm trying to solve is the conflict between limited inventory logistics and survival gear. The *bulky* system means there's very limited granularity for tracking, which is what I want most of the time but is fairly awkward for the specific case of survival and supplies.
        * The compromise was to add *uses* to a pack of Supplies, and to make the requirements for surviving nicely outside more specific.
    * Removed the bit about adding up Direct Damage when suffering simultaneous attacks.
        * I already removed the *gang up* rule from Electric Bastionland and Cairn, and this simply swung too far in the opposite direction.
        * Instead there's now a reminder that the Critical Damage Save could be *impaired* if suffering attacks from multiple attackers, which more or less solves the problem I was trying to fix in the first place.
            * This isn't actually a rule change, just a reminder (to myself, if no one else) that it's an option.
     * Update to "initiative" rules.
        * Players now always go fist
        * DEX Save to avoid surprise and skip the first round.
     * Adjustments to "Second Sight" Advanced Abilities
        * When three players in the same playtest all picked similar, but subtly different "second sight" abilities I realized I should probably differentiate them more.
            * Crystal Wizard's **Crystal Sight** is now **Crystal Vibes**
            * Soulbearer's **Soulsight** has a more specific limitation.
            * Demonic Sorcerer's **Demonic Sight** is now **Demonic Senses**
    * Out of Combat Damage rules
        * Added to both Combat (hah) and GM Guidance sections.
        * Bypasses Grit and simply inflicts Critical Damage immediately.
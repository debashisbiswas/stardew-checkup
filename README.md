# stardew-checkup

## About Stardew Checkup

This app checks a [Stardew Valley](http://stardewvalley.net/) save file for various achievements and milestones and lets you know what is missing. Currently it checks for progress on 38 achievements (everything but the 2 Praire King minigame achieves) as well as Grandpa's evaluation. It also summarizes relationship progress, including cutscenes.

All changed & added content from version 1.3 should be supported, including output for all players in a multiplayer save; 1.3-specific features will only appear in the results if the save is detected to be from that version. Please report any bugs, suggestions, or other feedback to the [topic in the official forums](https://community.playstarbound.com/threads/webapp-stardew-checkup-achievement-completion-progress.141706/).

The app is written in Javascript and uses [jQuery](https://jquery.com/) it is hosted on GitHub Pages at https://mouseypounds.github.io/stardew-checkup/ and the source code repository is https://github.com/MouseyPounds/stardew-checkup/. It is released under the MIT license.

## Changelog

*  1 Sept 2018 - v2.2.1 - Detect crafting recipes from mods; collapse older entries in changelog
* 29 Aug  2018 - v2.2.0 - Added the polyamory events to social summary & clarified multi-NPC events
* 20 Aug  2018 - v2.1.2 - Blobfish spelling fix and better input sanitization
* 12 Aug  2018 - v2.1.1 - Another bugfix for fish count (Pearls)
* 12 Aug  2018 - v2.1.0 - Individual player output can now be toggled on/off on multiplayer saves
* 11 Aug  2018 - v2.0.2 - Bugfix in fish count related to Secret Notes
* 25 June 2018 - v2.0.1 - Sanity-checking on cooking results and NPCs
*  6 June 2018 - v2.0.0 - Multiplayer support for all relevant sections
* 26 May  2018 - v1.9.7 - Secret Note reward bugfixes
* 24 May  2018 - v1.9.6 - Secret Note reward progress; favicon; change initial spouse friendship max to stardrop threshold
* 21 May  2018 - v1.9.5 - Work around multiplayer mine level weirdness; add "angry" status after confrontation event
* 14 May  2018 - v1.9.4 - Fix quest completion for SV 1.2 that got broken in last update
* 12 May  2018 - v1.9.3 - Fix quest completion to only look at host
* 10 May  2018 - v1.9.2 - Friendship status, including "guesses" for 1.2
*  4 May  2018 - v1.9.1 - Additional support for version 1.3 features (work in progress)
*  1 May  2018 - v1.9 - Basic support for version 1.3 (fix friendship parsing); new content support will come later
* 14 Apr  2018 - v1.8 - Rusty Key counter on museum summary and minor formatting changes
*  9 Mar  2018 - v1.7 - Added "heart events" to Social friendship summary
*  7 Feb  2018 - v1.6 - Wiki links for social summary and additional info on current skill level
* 29 Jan  2018 - v1.5 - Added full friendship point summary to Social section
* 10 Sept 2017 - v1.4 - Minor bugfixes
* 28 June 2017 - v1.3 - Added navigation links along right side (only visible after a save is loaded)
* 27 June 2017 - v1.2 - Community Center bundle & Joja Mart form progress
* 23 June 2017 - v1.1 - Added wiki links for needed item lists
* 22 June 2017 - v1.0 - Initial Release
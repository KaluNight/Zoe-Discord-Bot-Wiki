---
title: Zoe Development Status
description: If you are interested in what features await you in the future, you can get an insight here.
published: true
date: 2023-08-19T16:26:00.875Z
tags: dev, status, dev status, development, development status, future, next features
editor: markdown
dateCreated: 2023-05-11T20:07:22.784Z
---

# Indicators

| Indicator | Meaning | Description |
| --- | --- | --- |
| ⚪   | **Scheduled** | We are aware of this feature/change and have it planned for a patch. |
| 🔴  | **Delayed** | We have determined that we need to delay this feature/change until a later date. |
| 🟡  | **In Development** | The feature/change is currently being worked on. |
| 🔵  | **In Testing** | The feature/change is currently being tested for bugs and functionality. |
| 🟢  | **Done** | The feature/change is ready for use and we are preparing for the patch. |
| ⭐   | **Early Access** | The feature/change is currently only available for early access servers/users. |
| 🏁  | **Deployed** | The feature/change is made available to all Zoe users. |

<br>

# Scheduled future changes

> Generally, the changes listed on this page are implemented. However, we do not guarantee that this is always the case. We would also like to point out that we reserve the right to make small changes to the schedule. Thank you for your understanding.
>{.is-warning}

> Here are ideas listed which we have already been planned for a patch.
>{.is-info}

<br>



### <span style="color:#1565c0">1.13.3</span> &nbsp; <span style="color:#757575"> Fixes</span>

-   🏁 **Internal**: Optimise database usage to avoid slowdowns (Will continue even after being deployed)
-   🏁 **Fix**: Champion analysis
-   🏁 **Fix**: Simplify subscription embed to make it more clear overall
-   🏁 **QoL**: Discord namechange > display usernames correctly
-   🏁 **Fix**: Add option to disable rank update or select in which interval it is sent in the rankchannel
-   🏁 **Fix:** fix discord markdown issues on leaderboards
-   🏁 **Fix**: Correct period strings when using the rankupdate command

<br>

### <span style="color:#1565c0">1.14</span> &nbsp; <span style="color:#757575"> AI Match Summary and Quality of Life</span>

-   🟡 **Feature**: AI Match Summary (summarizes a game in text in a way that you can choose)
-   ⚪ **Feature**: Adding Champion analysis as seperate command
-   ⚪ **QoL**: Add recent playtime. recent most played champions and total, normal and soloQ winrate to /stats profile command
-   ⚪ **QoL**: Add another digit to make average KDA more detailed
-   ⚪ **QoL**: Improve team-analysis to add several players in one command
-   ⚪ **QoL**: Increase listed matches in matchhistory command (5 > 10)
-   ⚪ **QoL**: Small change to matchhistorychannel and command to increase visibility of KDA
-   ⚪ **QoL**: Auto refresh after /register was done to instantly add the registered player to infopanel and give their rank.
-   ⚪ **QoL**: Add a setting that allows to enable the command to add a player to a team for everyone

<br>

### <span style="color:#1565c0">1.14.1</span> &nbsp; <span style="color:#757575">  Lane icons and automated Roles</span>

-   ⚪ **QoL**: Add lane icons to clashchannel, predictrole and team-analysis.
-   ⚪ **QoL**: New layout for /stats predictrole
-   ⚪ **Feature**: Lane roles: roles that are assigned to registered players based on what lanes they played in recent games.
-   ⚪ **Feature**: Rank Roles (Free, Premium and Peak-Elo): Add a "unranked/In Placements" role to the bottom of ranks that shows at season start & unranked players

<br>

### <span style="color:#1565c0">1.14.2</span> &nbsp; <span style="color:#757575"> More and better leaderboards</span> 
-   ⚪ **Feature**: Winrate leaderboard for winrate in general, per champion or per queue (Solo/Duo, Flex) in the last 30 days.
-   ⚪ **Feature**: Recent playtime leaderboard for playtime in general, per champion or per queue (Solo/Duo, Flex (TFT tbt.)) in the last 30 days.
-   ⚪ **Feature**: Average KDA leaderboard per queue (Solo/Duo, Flex (TFT tbt.))
-   ⚪ **Feature**: New way to create leaderboards for teams
-   ⚪ **QoL**: Add Mastery emotes and new filter option to mastery leaderboards

<br>

### <span style="color:#1565c0">1.14.3</span> &nbsp; <span style="color:#757575"> Patchnotes</span>

-   ⚪ **Feature**: League of Legends or/and TFT patchnotes are provided in a channel of your choice.

<br>

### <span style="color:#1565c0">1.14.4</span> &nbsp; <span style="color:#757575"> Matchhistorychannel</span>

-   ⚪ **QoL**: Display MHC runes only in detailed view
-   ⚪ **Config**: create a setting to choose which view is displayed by default

<br>

### <span style="color:#1565c0">1.15</span> &nbsp; <span style="color:#757575"> More and better advice and analysis</span>

-   ⚪ **Feature**: Early game advice
-   ⚪ **Feature**: team- and clashanalysis of possible matchups, advantages and disadvantages
-   ⚪ **Feature**: Include counters & full item builds to champion analysis
-   ⚪ **QoL**: Automatically analyse enemies in clashchannel

<br>



>That's it for now. 
If you have ideas for new features or suggestions for improvements, please let us know on the Discord server in the `#requests-feedback` channel.
>{.is-success}

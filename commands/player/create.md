---
title: /create player - Command
description: Information about the /create player command
published: true
date: 2025-02-10T19:37:29.391Z
tags: create, command, player
editor: markdown
dateCreated: 2024-04-22T15:54:53.356Z
---

# /create player @DiscordUser region gamename tag
## Information
**This command is used to create a player.  To do this, you must enter the appropriate data for `@DiscordUser`, [`region`](/en/terms/region), [`gamename and tag (Riot ID)`](/en/terms/riotid) to link a League of Legends account to a member of your discord server. You can find all server region tags here: [Regions](/en/terms/region)**

**This command is meant to be for administrators that want to create the account for their players.**
<br>

### Permissions needed:
>**Manage channels** - only users with this permission ("moderators"/"administrators") can use this command as it affects Zoe for the server more deeply {.is-warning}

<br>

## Usage
<div class="discord-preview">
    <div class="dcp-chatbar">
        <img src="/zoe_logo.png" class="dcp-avatar">
        <span class="dcp-command">/create player</span>
        <div class="dcp-args">
            <div class="dcp-arg">
                <span class="dcp-arg-label">user</span>
                <span class="dcp-arg-value">
              	<span class="dcp-mention">@timfernix</span>
              </span>
            </div>
          <div class="dcp-arg">
                <span class="dcp-arg-label">region</span>
                <span class="dcp-arg-value">EUW</span>
            </div>
          <div class="dcp-arg">
                <span class="dcp-arg-label">game-name</span>
                <span class="dcp-arg-value">Star Guardian Ez</span>
            </div>
          <div class="dcp-arg">
                <span class="dcp-arg-label">tag</span>
                <span class="dcp-arg-value">real</span>
            </div>
        </div>
        <button class="dcp-send-btn">&#10148;</button> 
    </div>
</div>

###### Arguments
| Argument | Required | Description |
|----------|----------|-------------|
| `user` | :heavy_check_mark: | The Discord mention of the [player](/en/terms/player) you want to create |
| `region` | :heavy_check_mark: | The [regiontag](/en/terms/region) of the [region](/en/terms/region) the player is in |
| `game-name` | :heavy_check_mark: | The first part of the [players](/en/terms/player) [Riot ID](/en/terms/riotid) |
| `tag` | :heavy_check_mark: | The second part of the [players](/en/terms/player) [Riot ID](/en/terms/riotid) |
<br>
 
## Related commands/pages:
- [/delete player](/en/commands/player/delete)
{.links-list}
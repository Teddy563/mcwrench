---
name: NEZNAMY/TAB wiki
slug: tab
source_url: https://raw.githubusercontent.com/wiki/NEZNAMY/TAB/Home.md
fetched_at: 2026-09-21T09:40:57.557Z
adapter: github-wiki
---
# NEZNAMY/TAB wiki — condensed reference
> Condensed by mcwrench/learn-plugin-docs from <https://raw.githubusercontent.com/wiki/NEZNAMY/TAB/Home.md>. Full text in RAW.md. Verify against the live docs for anything safety-critical.

## Overview

## About the wiki
The wiki explains the functionality of the plugin as of version **6.2.0**.
If your config looks different or is missing some features, you are using an old version of the plugin.
To get the latest version, check [releases](https://github.com/NEZNAMY/TAB/releases/).  
Wiki for older plugin versions is not available.

If you plan to run your server for longer than 1 week,
it's a good idea to read this wiki as it explains everything about the plugin.
This will give you knowledge to do things you had no idea were possible, giving you an advantage over everyone else.

A lot of examples on the wiki use PlaceholderAPI placeholders without explaining its installation step by step. If you are going to use the examples and aren't familiar with the plugin, check out [Quick PlaceholderAPI startup guide](https://github.com/NEZNAMY/TAB/wiki/Quick-PlaceholderAPI-startup-guide).

## Installation

## Getting started
* [Why TAB?](https://github.com/NEZNAMY/TAB/wiki/Why-TAB%3F)
* [Installation](https://github.com/NEZNAMY/TAB/wiki/Installation)  
* [Commands & Permissions](https://github.com/NEZNAMY/TAB/wiki/Commands-&-Permissions)  
* [Frequently Asked Questions](https://github.com/NEZNAMY/TAB/wiki/Frequently-Asked-Questions)  
* [Compatibility](https://github.com/NEZNAMY/TAB/wiki/Compatibility)
* [How to assign players into groups](https://github.com/NEZNAMY/TAB/wiki/How-to-assign-players-into-groups)  
* [Known issues](https://github.com/NEZNAMY/TAB/wiki/Known-issues)
* [TAB-Bridge plugin](https://github.com/NEZNAMY/TAB/wiki/TAB-Bridge)

## Details

## NEZNAMY/TAB (wiki)

## Terminology
On order to not have to explain something every time it is mentioned, it will be explained here once.
| Name           | Description           |
|----------------|-----------------------|
| proxy server   | Server running BungeeCord or Velocity software, which are used to connect multiple servers, allowing easy transfer between them. |
| modded server  | Fabric, Forge and NeoForge. |
| backend server | Minecraft server that is actually being played on, not a proxy. This includes Bukkit (and its forks) and modded servers |

## Limitations of plugins
TAB is a plugin (even on modded platforms, it is only a server-sided mod).
It only modifies the server behavior to your liking.
It does not add anything into the game.
Because of that, you'll need
to carefully read the limitations of each feature to know what they are capable of and what they are not capable of.
Some of the undesired behavior can be altered using a resource pack and some using a modified client.
Both of these are out of scope of TAB as a plugin; therefore, no advanced information regarding this is provided.

## Public plugin
TAB is a public plugin designed to satisfy the needs of a majority of servers.

This means it has functions not everyone will need. All you need to do is disable functions you don't want. Disabled features do not consume the CPU at all.

On the other hand, it cannot contain everything everyone can think of.
There must be a balance
between providing as much as possible while making the configuration as short and readable as possible.
This is not an easy task.
The majority of things that are not supported directly can be achieved in different ways.
Adding direct way for everything everyone asks for would not only take a lot of time,
but make the plugin harder to configure for everyone, as well as introduce a lot of duplicate ways to achieve things,
making the plugin overcomplicated.  
If your need is very specific and not available in the plugin in any way,
you should look into private plugin development.
You will end up with a plugin made just for you with everything you want and nothing else.

## Wiki pages

## Core features
* [Belowname](https://github.com/NEZNAMY/TAB/wiki/Feature-guide:-Belowname)
* [Bossbar](https://github.com/NEZNAMY/TAB/wiki/Feature-guide:-Bossbar)
* [Global playerlist](https://github.com/NEZNAMY/TAB/wiki/Feature-guide:-Global-playerlist)
* [Header/Footer](https://github.com/NEZNAMY/TAB/wiki/Feature-guide:-Header-&-Footer)
* [Layout](https://github.com/NEZNAMY/TAB/wiki/Feature-guide:-Layout)
* [Multi server support](https://github.com/NEZNAMY/TAB/wiki/Feature-guide:-Multi-server-support)
* [Nametags](https://github.com/NEZNAMY/TAB/wiki/Feature-guide:-Nametags)
* [Per world playerlist](https://github.com/NEZNAMY/TAB/wiki/Feature-guide:-Per-world-playerlist)
* [Ping spoof](https://github.com/NEZNAMY/TAB/wiki/Feature-guide:-Ping-Spoof)
* [Playerlist objective](https://github.com/NEZNAMY/TAB/wiki/Feature-guide:-Playerlist-Objective)
* [Scoreboard](https://github.com/NEZNAMY/TAB/wiki/Feature-guide:-Scoreboard)
* [Sorting in tablist](https://github.com/NEZNAMY/TAB/wiki/Feature-guide:-Sorting-players-in-tablist)  
* [Spectator fix](https://github.com/NEZNAMY/TAB/wiki/Feature-guide:-Spectator-fix)
* [Tablist name formatting](https://github.com/NEZNAMY/TAB/wiki/Feature-guide:-Tablist-name-formatting)

## Functions
* [Animations](https://github.com/NEZNAMY/TAB/wiki/Animations)
* [Component usage (RGB, fonts, sprites)](https://github.com/NEZNAMY/TAB/wiki/How-to-use-Minecraft-components)
* [Conditional placeholders](https://github.com/NEZNAMY/TAB/wiki/Feature-guide:-Conditional-placeholders)
* [Error logging](https://github.com/NEZNAMY/TAB/wiki/Error-logging)  
* [MySQL](https://github.com/NEZNAMY/TAB/wiki/MySQL)
* [Placeholder output replacements](https://github.com/NEZNAMY/TAB/wiki/Feature-guide:-Placeholder-output-replacements)
* [Placeholders](https://github.com/NEZNAMY/TAB/wiki/Placeholders)

## Other
* [Additional information](https://github.com/NEZNAMY/TAB/wiki/Additional-information)
* [Bedrock compatibility](https://github.com/NEZNAMY/TAB/wiki/Bedrock-compatibility)
* [Client-sided mechanics](https://github.com/NEZNAMY/TAB/wiki/Client%E2%80%90sided-mechanics)
* [Developer API](https://github.com/NEZNAMY/TAB/wiki/Developer-API)
* [How to display name from nickname plugins](https://github.com/NEZNAMY/TAB/wiki/How-to-display-name-from-nickname-plugins)
* [How to save config in UTF-8 encoding](https://github.com/NEZNAMY/TAB/wiki/How-to-save-the-config-in-UTF8-encoding)
* [How to set up compatibility with glow plugins](https://github.com/NEZNAMY/TAB/wiki/How-to-make-TAB-compatible-with-glow-plugins)
* [Mini guides collection](https://github.com/NEZNAMY/TAB/wiki/Mini-guides-collection)
* [Optimizing plugin's CPU usage](https://github.com/NEZNAMY/TAB/wiki/Optimizing-the-plugin)
* [Quick PlaceholderAPI startup guide](https://github.com/NEZNAMY/TAB/wiki/Quick-PlaceholderAPI-startup-guide)

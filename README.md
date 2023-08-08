# Discord OSINT
OSINT Discord resources that may be useful for searching or pivotting on Discord.
## 📖 Table of Contents

* [Tools for searching groups, messages](#-tools-for-searching-groups-and-messages)
* [Tools for searching bots](#-tools-for-searching-bots)
* [Tools for searching for users and information about them](#-tools-for-searching-for-users-and-information-about-them)
* [Discord OSINT attack surface](#-discord-osint-attack-surface)
* [Discord Dorks](#-discord-dorks)
* [Get Discord user ID](#-get-discord-user-id)
  * [Using the Mobile App](#-using-the-mobile-app)
  * [Using the Desktop App](#-using-the-desktop-app)
* [Discord Bots for OSINT](#-discord-bots-for-osint)
* [Discord scam links](#-discord-scam-links)
* [Notes](#-notes)
* [Discord Wiki](#-discord-wiki)

![OSINT Discord logo](https://github.com/wddadk/Discord-OSINT/blob/main/sources/Discord.png)

Discord official website: https://discord.com/

## [↑](#-table-of-contents) Tools for searching groups and messages

* [Discordbee](https://discordbee.com/)
* [Discordservers](https://discordservers.com/browse)
* [Discord.me](http://discord.me)
* [Discordportal](http://discordportal.com)
* [Discord.Center](http://discord.center)
* [Disboard](https://disboard.org/search)
* [Dsc.gg](https://dsc.gg/)
* [Discords](https://discords.com/)
* [Discordleaks.unicornriot](https://discordleaks.unicornriot.ninja/discord/users) - Finds servers and messages
* [Discord History Tracker](https://dht.chylex.com/) - Discord History Tracker is a browser script that lets you locally save chat history in your servers, groups, and private conversations. + [Github](https://github.com/chylex/Discord-History-Tracker)
* [Unfurl](https://dfir.blog/unfurl/) - If you have any URLs of interest from Discord, you can potentially extract additional timestamp info. Each Discord ID (for user, channel, server, or file attachment) has an embedded timestamp that shows when that object was created.
* [Pixelatomy.com](https://pixelatomy.com/snow-stamp/) - Snowflake Timestamp converter + [official documentation](https://discord.com/developers/docs/reference#snowflakes)

## [↑](#-table-of-contents) Tools for searching bots
* [Top.gg](https://top.gg/) - Search for Discord servers/bots
* [discordbotlist](https://discordbotlist.com/)
* [Discordbots](https://discord.bots.gg/)

## [↑](#-table-of-contents) Tools for searching for users and information about them
* [Discordlookup](https://discordlookup.com/user)
* [Id.nerrix](https://id.nerrix.ovh/)
* [Discord-tracker](https://discord-tracker.com/) - gives the registration date, activity statistics, servers in which the account participates, name history, avatar history, voice events, messages, popular words, possible friends, activity statistics, and so on
* [Discords](https://discords.com/bio) - Discord Profile List
* [DiscordHub](https://discordhub.com/user/search) UPD - 07.08: Not working

## [↑](#-table-of-contents) Discord OSINT attack surface

[Discord OSINT attack Surface PDF](https://github.com/wddadk/Discord-OSINT/blob/main/sources/Discord%20OSINT%20Attack%20Surface%20(1).pdf) - Attack surface options

## [↑](#-table-of-contents) Discord Dorks
**from:** user - Shows results from a specific user.

**mentions:** user - Shows anytime someone mentioned the specified user.

**has:** link, embed or file - Shows messages that contain specified element.

**before:** date - Results only show messages sent before specified date.

**during:** date - Results only show messages sent on specified date.

**after:** date - Results only show messages sent after specified date.

**in:** channels - Results only show messages sent in specified channel.

## [↑](#-table-of-contents) Get Discord user ID

#### [↑](#-table-of-contents) Using the Mobile App
For the User ID, go to a user's Profile. You should see three dots on the top-right. Press those dots and you should see the last item on the drop-down menu: 'Copy ID'. Click this to get the ID. Paste in text editor to see the ID.

![Telegram Id](https://github.com/wddadk/Discord-OSINT/blob/main/sources/discordid.png)

#### [↑](#-table-of-contents) Using the Desktop App
Log into a Discord Channel. Right click your username in chat or channel list. Select Copy ID. Paste the ID somewhere to see it.

![Telegram Id PC](https://github.com/wddadk/Discord-OSINT/blob/main/sources/discordidpc.png)

[support.discord.com](https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-) — instructions on how to find the Discord account ID
*Sometimes you will need to set your account to developer mode first to be able to right-click a username and select Copy ID. Visit: - Settings -> Appearance -> and toggle ON developer mode.*

## [↑](#-table-of-contents) Discord Bots for OSINT

[GitOSINT_Bot](https://github.com/C3n7ral051nt4g3ncy/GitOSINT_Bot)- GitOSINT is a Discord bot that helps you to find information/intelligence.

## [↑](#-table-of-contents) Discord scam links
* [Discord-AntiScam](https://github.com/Discord-AntiScam/scam-links)
* [Scam-links](https://github.com/DevSpen/scam-links/)

## [↑](#-table-of-contents) Notes
* [Since 2023 discord is changing it's nickname policy and replacing (nickname#numer) with (nickname)](https://support.discord.com/hc/en-us/articles/12620128861463-New-Usernames-Display-Names)
* Because of the "gaming" nature of Discord's audience, there are a lot of:
  - bots with all sorts of additional commands
  - sites integrated with the server, showing all sorts of member's achievements, leaderboards, etc...
* [Discord status](https://discordstatus.com/) - Check Global discord uptime status for the API, media proxy, push notifications, search, voirce & third party
## [↑](#-table-of-contents) Discord Wiki
[Discord Wiki](https://discordia.me/en/home) - Great in depth wiki about all Discord has to offer. 

-----------------------------------------------------------------------------------------------------------------------------------------------
Inspired by [@Dutchosintguy](http://twitter.com/dutch_osintguy) and [@AtonceInventions](https://github.com/AtonceInventions)

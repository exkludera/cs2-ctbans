## discontinued project, check out [playpark/cs2-ctbans](https://github.com/playpark/cs2-ctbans)

<br>

> [!NOTE]
> * permission in config is now being used for cmds
> * new config setting for own dbtable name
> * color support in config tag
> * changed database table structure + added player name, admin name & time added
> * cleaned up code and fixed grammar stuff
> * ban time is now in minutes instead of hours
> * expired bans wont disappear from database
> * added localizers 
> * custom command triggers
> * read commits for other changes

<br>

> [!IMPORTANT]
> FORK FROM [DeadSwimek/cs2-ctban](https://github.com/DeadSwimek/cs2-ctban)

<img src="https://github.com/user-attachments/assets/53e486cc-8da4-45ab-bc6e-eb38145aba36" height="200px"> <br>

<br> <a href="https://ko-fi.com/exkludera" target="blank"><img src="https://cdn.ko-fi.com/cdn/kofi5.png" height="48px" alt="Buy Me a Coffee at ko-fi.com"></a>

## old readme from main below
--------------------------------------------

# TBans
[CLICK TO ALTERNATIVE T BANS](https://github.com/DeadSwimek/cs2-tban)

##### Lists of my plugins
> [VIP](https://github.com/DeadSwimek/cs2-vip), [VIP Premium](https://github.com/DeadSwimek/cs2-vip-premium), [SpecialRounds](https://github.com/DeadSwimek/cs2-specialrounds), [Countdown](https://github.com/DeadSwimek/cs2-countdown), [CTBans](https://github.com/DeadSwimek/cs2-ctban), [HideAdmin](https://github.com/DeadSwimek/cs2-hideadmin)

> If you wanna you can support me on this link - **https://www.paypal.com/paypalme/deadswim**

### Features

- Can banning player to connect in CT Team
- Can unbanning player to connect in CT Team
- Session banning the player
- Database maked
- Can make banlist


# Donators
***GreeNyTM*** Value **200 CZK**

# Commands
**css_ctban**

`Usage: /ctban <SteamID/PLAYERNAME> <Hours> 'REASON'`

**css_unctban**

`Usage: /unctban <SteamID>`

**css_isctbanned**

`Usage: /isctbanned <SteamID>`

**css_ctsessionban**

`Usage: /ctsessionban <PLAYERNAME> <REASON>`

| Command      | Permission   |
| ------------ | ------------ |
| `css_ctban`    | @css/ban     |
| `css_unctban`    | @css/ban     |
#Config

```JSON
{
  "Prefix": " \u0001[\u0004MadGames.eu\u0001]",
  "permission": "@css/reservation",
  "DBDatabase": "database",
  "DBUser": "user",
  "DBPassword": "password",
  "DBHost": "localhost",
  "DBPort": 3306,
  "ConfigVersion": 1
}
```


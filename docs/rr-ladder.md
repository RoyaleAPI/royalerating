# Royale Rating Ladder

This is a tournament-standard custom Ladder which calculates your skill rating by playing Clash Royale games. The rating system is similar to Elo but is much more advanced and can hone into your rating more accurately and quickly.

Please join this Discord server to participate in user-testing: http://discord.gg/BFGzZpn

| Command | Description |
| --- | -- |
| `!!rr verify [player_tag] [api_token]` | Verify account |
| `!!rr register [series_name]` | Register to play in series |
| `!!rr play [another_user]` | Play against specific user |
| `!!rr seek` | Seek a game where anyone can accept |
| `!!rr leaderboard` | Display leaderboard |
| `!!rr playerinfo` | Player information for yourself or another player |

## Register and Play

Testing will happen on the bot named `R3.Alpha`. This bot uses the prefix `!!` so prepend all your commands with `!!`. All of the commands starts with `!!rr` followed by a subcommand.

### Verify

You must verify that you own the account in order to play. You will need:

- Player tag
- API token

```
!!rr verify [player_tag] [api_token]
!!rr verify C0G20PR2 anb8czxg
```

<img src="/img/rr/tag-api-token.png" style="width:100%; height: auto">


### Register

After you have verified your account ownership, you can register to a series to play. Current active series is `a2`

```
!!rr register a2
```

### Play

To play against another opponent:

```
!!rr play @alpe123#2295
```

- Your opponent will be asked to accept the match.
- If the match is accepted, you have 2 minutes to open CR and play the game.
- Once the game is completed, your ratings will be updated.

### Seek

Open seek: allows you to post a match and allow anyone else to accept

```
!!rr seek
```
- Anyone can react with ✅ to accept your seek
- If you wish to cancel your seek, you can react with 🚫

<img src="/img/rr/rr-seek.png" style="width:100%; height: auto">

### Leaderboard

```
!!rr Leaderboard
!!rr lb
```

<img src="/img/rr/rr-leaderboard.png" style="width:100%; height: auto">

### Player Info

```
!!rr playerinfo
!!rr pi
!!rr playerinfo @alpe123#2295
!!rr pi @alpe123#2295
```

<img src="/img/rr/rr-playerinfo.png" style="width:100%; height: auto">

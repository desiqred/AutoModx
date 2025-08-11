# AutoModX - Discord Auto Moderation Bot

AutoModX is a basic yet powerful Python Discord bot with **10+ moderation commands** to help manage your server with ease.  
It’s built using [`discord.py`](https://pypi.org/project/discord.py/) and designed for speed, simplicity, and expandability.

---

## Features
✅ Kick, Ban, Unban members  
✅ Mute & Unmute users  
✅ Clear messages in bulk  
✅ Issue & view warnings  
✅ Slowmode control  
✅ Lock & Unlock channels  
✅ Permission-based command usage  

---

## Commands
| Command | Description | Permission Required |
|---------|-------------|---------------------|
| `!kick <member> [reason]` | Kicks a member | Kick Members |
| `!ban <member> [reason]` | Bans a member | Ban Members |
| `!unban <username#discriminator>` | Unbans a member | Ban Members |
| `!mute <member> [reason]` | Mutes a member | Manage Roles |
| `!unmute <member>` | Unmutes a member | Manage Roles |
| `!clear <amount>` | Clears recent messages | Manage Messages |
| `!warn <member> [reason]` | Warns a user | Kick Members |
| `!warnings_list <member>` | Shows warnings | Kick Members |
| `!slowmode <seconds>` | Sets slowmode delay | Manage Channels |
| `!lock` | Locks current channel | Manage Channels |
| `!unlock` | Unlocks current channel | Manage Channels |

---

## Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/desiqred/AutoModX.git
   cd AutoModX

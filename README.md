if you want use this P2P CHAT execute this commands:
for termux:

pkg update && pkg upgrade
pkg install git -y && pkg install mono-complete -y && pkg install python -y && git clone https://github.com/kerem1545-pvd/P2P-Chat.git && cd P2P-Chat && mono p2p_chat.exe

features:

💎 no need port foward
💎 anti ddos + E2EE
💎 host commands
💎 remember host feature

### 👑 Host (Admin) Commands
> These commands can only be executed by the room creator (Host).

| Command | Usage Example | Description |
| :--- | :--- | :--- |
| `!kick <username>` | `!kick ahmet` | Kicks the user from the room immediately. |
| `!ban <username>` | `!ban mehmet` | Bans the user (kicks them and prevents them from rejoining). |
| `!unban <username>` | `!unban mehmet` | Removes the user from the ban list. |
| `!mute <username>` | `!mute troll123` | Mutes the user (their messages are blocked and ignored by peers). |
| `!unmute <username>` | `!unmute troll123` | Unmutes the user, allowing them to send messages again. |
| `!maxusers <number>` | `!maxusers 8` | Sets the maximum capacity of the room (blocks new joins when full). |
| `!whitelist on` | `!whitelist on` | Activates whitelist mode (non-whitelisted users are kicked/blocked). |
| `!whitelist off` | `!whitelist off` | Deactivates whitelist mode. |
| `!wl add <username>` | `!wl add alex` | Adds a user to the whitelist. |
| `!wl remove <username>` | `!wl remove alex` | Removes a user from the whitelist. |

---

### 💬 General / Member Commands
> These commands are available to all room participants.

| Command | Usage Example | Description |
| :--- | :--- | :--- |
| `!help` | `!help` | Displays the help menu with all available commands. |
| `!users` | `!users` | Lists all online participants in the room and shows the room capacity. |
| `!wllist` | `!wllist` | Displays current whitelist status (Enabled/Disabled) and allowed users. |
| `!banlist` | `!banlist` | Displays the list of all currently banned users. |
| `!mutelist` | `!mutelist` | Displays the list of all currently muted users. |
| `!claimhost <password>` | `!claimhost mypass123` | Reclaims the Host/Admin role if the host reconnected to the room. |
| `exit` | `exit` | Leaves the chat session and terminates the P2P connection. |

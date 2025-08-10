# Zarco Discord App Overview

Zarco is a powerful and versatile Discord App built to streamline server management, automate common tasks, and enhance community interaction. It leverages modern Discord interaction features such as slash commands, buttons, modals, and select menus, eliminating the need for outdated prefix commands and delivering a clean, intuitive user experience.

---

## 🔧 Key Features

### 📦 Custom Embed Builder  
Design, edit, and share rich Discord embeds directly through an interactive interface. Supports exporting and importing embeds, allowing for quick replication and editing across servers or channels.

---

### 🎁 Giveaway Management  
Host giveaways with interactive buttons and real-time tracking. Zarco handles entries, automatically draws winners, and prevents alt or app abuse. All processes are handled through slash commands and buttons to maintain a seamless experience without spammy text commands.

---

### 📬 Modmail System  
Allow members to contact server staff privately through modals and DMs. Incoming messages are routed to dedicated staff channels while preserving privacy. Unlike traditional modmail apps, Zarco avoids storing message content and emphasizes in-server interaction and transparency.

---

### 👋 Member Greetings  
Automatically welcome new users and send departure messages using the Guild Members intent to track joins and leaves. Messages can be customized with dynamic variables (username, server name, etc.) to create a personalized and friendly onboarding experience.

---

### 🔊 Private Voice Channels (PVCs)  
Automatically creates a private voice channel for a user when they join a designated "lobby" voice channel. The private VC is deleted once empty, reducing clutter. Offers full customization of channel naming, user limits, and permissions.

---

### 😎 Emoji Management  
Upload, clone, rename, or delete emojis directly from the app without ever needing to visit Discord settings. All actions are performed in real-time through the Discord API with no data storage on external servers, making it fast and privacy-safe.

---

### 🛠️ Server Utilities  
Includes various helpful tools such as:  
- Viewing user avatars or banners  
- Retrieving server information  
- Checking the weather for any location  
- Translating messages in real-time using APIs  
All tools are accessible via slash commands and built for ease of use.

---

### 🎭 Role Assignment System  
Supports:  
- Autoroles (automatically assigning roles to new members)  
- Role selection menus for easy role management  
Designed for communities that require easy access to roles like languages, interests, or notification pings.

---

### 📜 Activity Logs (Audit Logs)  
Monitor important server events in real time such as:  
- Message edits and deletions  
- Role and channel changes  
- User joins/leaves  
- Moderator actions (bans, kicks, timeouts)  
Zarco does not store message content, ensuring user privacy while keeping staff informed of key events.

---

### 🛡️ Moderation Tools  
Includes a complete set of moderation commands:  
- /ban, /timeout, /warn, etc.  
These tools are simple for staff to use and respect Discord’s permissions model.

---

### 🔢 Counting Module  
Lets users count in sequence by sending numbers in a channel. The bot checks for correct order, deletes wrong entries, and announces milestones to keep the game engaging.

---

### /logs permission  
Allows moderators to select a channel where the bot sends notifications when moderation permissions are granted or revoked via roles or channel overwrites. Requires Guild Members intent to monitor these permission changes.

---

### 🎮 Mini Games  
Engage your members with a suite of casual games:  
- Tic-Tac-Toe (PvP)  
- Minesweeper  
- Connect 4  
- Rock-Paper-Scissors  
All games are played via buttons and interaction menus, ensuring a smooth, mobile-friendly experience.

---

## 📌 Key Benefits  
- Fully interaction-based: built with Discord’s modern features  
- Privacy-respecting: avoids logging message content  
- Designed for performance and scalability in active communities

---

## 🔗 Demo & Feature Showcase Links

### Giveaway system  
https://drive.google.com/file/d/1P6dEcguI57lUn-3_YNdSnU4KfGOcSWlR  
https://drive.google.com/file/d/1s1xKB9VhqAi27gkRRvmjYMHnCkkbA0gB  
https://drive.google.com/file/d/1Qy2M-ztFzOvzk0s7WOzCLeQsTu5hPysu  

### Modmail  
https://drive.google.com/file/d/1vhyPVZYzQazArVjezcIZWq1k_R2GmUwe  

### Private Voice Channels  
https://drive.google.com/file/d/1nrpwy8AJ55GlDLAGWNMITfpZv6IYeIiq  

### Emoji Tools  
https://drive.google.com/file/d/1fb9uhea8HGn3-i7SWnNw0SdBZNDlC3Xm  

### Custom Embed Builder  
https://drive.google.com/file/d/1aXdNH-CiXTrDjqGistOnd75JasZjmDXF  
https://drive.google.com/file/d/1tFCtFOArxzK23w-41AJHQbuv1WOsBm-u  

### Counting Game  
https://drive.google.com/file/d/1q82Vy-PC5Wt0KTujgFyazp1kED--dvRl  
https://drive.google.com/file/d/1MahhXAvHo5Aj8J3Rso3H_ccCH6Vn49ai  

### Role Assignment  
https://drive.google.com/file/d/1lODVSr9PMSxcXqYjpoIabHmdwCs7t0EN  
https://drive.google.com/file/d/1Fjr1CZ2R13lyNhzFbDKbqNIZUTupA0BV  
https://drive.google.com/file/d/1HxklJ2NN6afD9M7hZrV72QV8xQ1w9cLK  

### Audit Logs  
https://drive.google.com/file/d/13nihvwSjGgIrBTmYuTnIVJjqBm-5rpGQ  

---

## Examples

### A. Logs:

1. Running the /logs permission slash command.  
https://drive.google.com/file/d/1SLIvRYxBDiPrvKNPb2REWBHwavCUqYat  
https://drive.google.com/file/d/1BXbnHnb0YjnTIaxOjQgSeKsoBAev_nJg  

2. The confirmation message that the logs channel is set.  
https://drive.google.com/file/d/1LlROOaiDpMuzXhamIEFZMhXQW4WrAHZ1  

3. Permission Change Notification Example.  
https://drive.google.com/file/d/1UR4mcE8ynKRkZ3r-WWke-xcnR6KwJEr4  

---

### B. Welcome / Leave messages:

1. A new user joining the server.  
https://drive.google.com/file/d/1E3ZjL2q9uMyZB3mzzyc76zgunfKem6gj  

2. Message sent by the bot in the leave/goodbye channel.  
https://drive.google.com/file/d/1Eo2KGUtqX_gbMBnpmn57ovClAhj3tRF7  

---

### C. /role all Bulk Role Command:  
https://drive.google.com/file/d/1YNSPVlJQYOtMdagPeaH15WSbakddUNZs  

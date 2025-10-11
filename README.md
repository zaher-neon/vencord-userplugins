<div align="center">

![WOOOO](woooo.png)
# Vencord Plugins/Mods
My vencord custom plugins/mods, dont forget to leave a ***Star*** ⭐

</div>



### 🫣 [**HideServerActivity**](https://github.com/zaher-neon/vc-hideServerActivity):
Hides the "Activity" section from the server members list in Discord, including any activity cards like playing games, listening to music, or streaming.

### 🎩 [**QuestComplete (Beta)**](https://github.com/zaher-neon/vc-questComplete):
QuestComplete is a Vencord plugin that adds a “Spoof” button to the Quests tab in Discord, allowing you to complete quests without having to install or launch games/apps manually. Spoofing code adapted from [this gist](https://gist.github.com/aamiaa/204cd9d42013ded9faf646fae7f89fbb) by [aamiaa](https://gist.github.com/aamiaa).

## Installation Guide

You can check [Official Vencord](https://docs.vencord.dev/installing/) or do below stuff:

### Requirements

Before installing, make sure you have:

* [Node.js](https://nodejs.org/) **v16 or higher**
* [Git](https://git-scm.com/)
* [pnpm](https://pnpm.io/) — install via: `npm install -g pnpm`

### 1. Clone Vencord

```bash
# Clone the Vencord repository
git clone https://github.com/Vendicated/Vencord.git
cd Vencord

# Install dependencies
pnpm install
```

### 2. Add the Plugin

1. Inside the `src` folder create a new folder `userplugins` then create another one with any name:

   ```
   src/userplugins/[any name]/
   ```

2. Download or copy the plugin file 👉 `index.tsx`

3. Place the plugin file in the folder:

   ```
   src/userplugins/[any name]/index.tsx
   ```


### 3. Build and Inject

Close Discord App, Run the following commands in the **root directory** of your Vencord clone:

```bash
# Build the stuff
pnpm build

# Inject stuff in Discord
pnpm inject
```
### 4. Done Easy

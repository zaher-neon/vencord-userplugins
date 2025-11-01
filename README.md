
<div align="center">

![WOOOOOO](woooooo.png)
# Vencord Plugins/Mods [![Visits Badge](https://badges.strrl.dev/visits/zaher-neon/vencord-userplugins)](https://badges.strrl.dev)

My vencord custom plugins/mods, dont forget to leave a ***Star*** ⭐ 
</div>

> [!Note]
> My Plugins uses very optimized `MutationObserver` instead of `patches` and this is not efficient, I know I'm just a lazy coder, I will update them later to use `patches` for efficiency.

### 🫣 [**HideServerActivity**](https://github.com/zaher-neon/vc-hideServerActivity) Two Ways By CustomCSS or Plugin:
Hides the "Activity" section from the server members list in Discord, including any activity cards like playing games, listening, ect.

### 🎩 [**QuestComplete (Beta)**](https://github.com/zaher-neon/vc-questComplete):
QuestComplete is a Vencord plugin that adds a “Spoof” button to the Quests tab in Discord, allowing you to complete quests without having to install or launch games/apps manually, also complete video quests fatser before video ends. Spoofing code adapted from [this gist](https://gist.github.com/aamiaa/204cd9d42013ded9faf646fae7f89fbb) by [aamiaa](https://gist.github.com/aamiaa).

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

2. Download the plugin files 👉 `index.tsx`

3. Place the plugin file in the folder:

   ```
   src/userplugins/[any name]/index.tsx
   ```
> [!CAUTION]
> Sometimes the plugin has many files other than `index.tsx` ignore `README.md`, get them all and place them in the same folder


### 3. Build and Inject

Close Discord App, Run the following commands in the **root directory** of your Vencord clone:

```bash
# Build the stuff
pnpm build

# Inject stuff in Discord
pnpm inject
```
### 4. Select Stable
Just Hit `Enter` for stable

### Hooorraayy You Did It 🎉

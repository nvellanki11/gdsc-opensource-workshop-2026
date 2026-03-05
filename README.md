# 🧙‍♂️ Tornelius, The Open Sourcerer of Technica 🧙‍♂️

<p align="center">
    <img src="tornelius.png" alt="Tornelius, The Open Sourcerer of Technica" width="200"/>
</p>

Welcome to **Tornelius, The Open Sourcerer of Technica**, the workshop activity for **Open Sourcery @ Technica UMD 2025**!  

In this activity, you'll team up in small groups (2–4 people) to make an open-source contribution by adding a new *keyspell* to Tornelius, the Open Sourcerer of Technica.

Each group will be assigned a unique keyboard letter (e.g. `q`, `w`, `e`, …) and will customize a keyspell for it (a spell that casts when that letter key is pressed).

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#the-goal">The Goal</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li>
      <a href="#how-it-works">How It Works</a>
    </li>
    <li>
      <a href="#submitting-your-keyspell">Submitting Your Keyspell</a>
    </li>
  </ol>
</details>

<a id="the-goal"></a>

## 🏆 The Goal

When someone presses your assigned key:
1. A keyspell will appear to be cast from **Tornelius** (displayed at the bottom of the screen).
2. The keyspell will fly upward in a random direction at a random speed.
3. The keyspell should have a unique style and effect created by your group!

Through Git commits, we’ll combine everyone’s keyspells into this repository; true open-source magic.

<a id="getting-started"></a>

## 🔮 Getting Started

### 1. Clone this repository

In your terminal, type:

```bash
git clone https://github.com/Open-Sourcery-UMD/technica-workshop-2025.git
```

### 2. Open the folder for editing

Open the `technica-workshop-2025` folder in your IDE or text editor of choice (e.g., VSCode).

### 3. Open the `technica-workshop-2025/index.html` file on your laptop
You’ll see Tornelius on the screen. Pressing your group's assigned key will cast your group’s keyspell.

### 4. Find your spell file
Each keyspell corresponds to a key on the keyboard:
`qSpell.js`, `wSpell.js`, `eSpell.js`, `rSpell.js`, ..., `mSpell.js`.
Your group will be told which file to edit (e.g. `fSpell.js`).

### 5. Make your keyspell unique!
Inside your file, you’ll see commented sections like:

`// ADD STYLES HERE`

`// FEEL FREE TO CHANGE THESE`

These are where your creativity comes in!
You can:
- Change the color, size, or shape of the keyspell. (basic)
- Change the sound effect for when your keyspell is cast. (basic)
- Add animations, rotations, sparkles, or glow effects. (medium)
- Make it bounce off the walls or react to gravity. (advanced)
- Make it explode or multiply! (advanced)

Even if you do nothing, no worries; your assigned keyspell will still work as a simple black dot that flies upward with a *whoosh* sound.

<a id="how-it-works"></a>

## ⚙️ How It Works

`index.html` loads each keyspell file.

Each `_Spell.js` file listens for its key press and creates a visual element (div) that flies away from Tornelius.

You only need to modify your keyspell file; everything else is ready!

<a id="submitting-your-keyspell"></a>

## 🪄 Submitting Your Keyspell

Once you're happy with your keyspell:

Commit and push your changes:

```bash
git add fSpell.js
git commit -m "Customize fSpell: Fireball of Friendship"
git push origin main
```

After doing this, your changes will be reflected in everyone's repositories!

To try out everyone else's spells, you can pull the most recent changes from the codebase:

```bash
git pull
```

Happy hacking!

— Open Sourcery

<a href="https://linktr.ee/umdopensourcery" target="_blank">https://linktr.ee/umdopensourcery</a>
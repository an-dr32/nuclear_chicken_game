# 🐔 Nuclear Chick-EN: The Bullet-Hell Breakfast Battle

***SHOW US YOUR TOP SCORE IN THE SCORES THREAD IN ISSUES***

Welcome to **Nuclear Chick-EN**, the fast-paced top-down shooter where one genetically-enhanced chicken must defeat waves of mutant sheep in a desperate fight for the future of breakfast, supper, and dinner.

This game is:
- 🕹️ A love letter to classic arcade chaos
- 🐑 Packed with mutant enemies
- 💥 Loaded with explosions, dashes, and bullet fury
- 🧠 Surprisingly readable and mod-friendly Phaser 3 code

---

## 🎮 How to Play

Your mission: **Survive as long as you can** while destroying mutant sheep, dodging chaos, collecting ammo crates, and maintaining your health.

| Action        | Controls                            |
|---------------|-------------------------------------|
| Move          | `W`, `A`, `S`, `D` or Arrow Keys    |
| Shoot         | `Spacebar` or Right-Click or  Touch |
| Dash          | `B` or `Shift`                      |
| Switch Music  | `P`                                 |
| Mute Music    | `M`                                 |
| Start Game    | `Enter` or Click on START           |

> Tip: Keep moving and dashing to stay alive. Dash = invincibility frames!

---

## 🧠 How the Code Works

The game is built using [Phaser 3](https://phaser.io), a fast HTML5 game framework.

### ✨ Key Features in the Code

- **Dynamic Waves**: Enemies get faster and spawn more often as you survive.
- **Crate & Health System**: Ammo and healing drop with animated sparkle.
- **Dash Mechanic**: Gives you a burst of speed and temporary invincibility.
- **Out-Smart The Enemy**: Enemies will launch towards you randomly.
- **Squash-and-stretch ready**: The framework supports juicy effects.
- **Custom Music Tracks**: 8 chiptune-inspired songs with switch and mute control.

### 📁 Code Structure

Everything lives in one HTML file for now:

- `index.html`: Contains all game logic in a Phaser.Scene.
- Assets are loaded dynamically from the `assets/` folder.
- Code is commented and organized into sections:
  - preload()
  - create()
  - update()
  - custom methods like `shootBullet`, `spawnEnemy`, `collectCrate`

---

## 🚀 How to Run It

1. Clone this repo:

   ```bash
   git clone https://github.com/an-dr32/nuclear_chicken_game.git
   cd nuclear-chick-en

2. You'll need a local server (recommended for audio + performance):

   ```bash
   npx http-server

4. Then visit http://localhost:8080


🐣 Customization & Hacking
Want to make it your own?

  - Change the background? Swap out assets/background.png.

  - Add power-ups? See spawnCrate() and collectCrate().

  - Make it rain bacon? You're the boss now.

  - Add your own soundtrack? Replace the MP3s in /assets/sounds/ and update the allTracks array.


💀 Victory & Game Over
You lose when your chicken runs out of health.

  - A tombstone marks your sacrifice.

But hey, there's always one more round.


📦 Assets
Sprites and sound effects are a mix of original and AI Generated art.

  - Make sure to replace these if you’re planning to publish your own version.


❤️ Credits & Shoutouts
Game design: Andres DM AKA Logg3r

  - Built with: Phaser 3

  - Soundtrack: Chiptune Madness by musicful.ai

Special thanks to: Me, Myself, and A.I.


🧪 TODO (For Contributors)

   - Add boss enemies every 10 waves

   - Upgrade weapons system

   - Mobile support

   - Juice it up with screen shake and camera bobbing

   - Use Electron to create a playable game without the need of a server.

***Default copyright laws, apply, meaning
The owner of this repository retains all rights, to the source code and no one may reproduce, 
distribute, or create derivative works from this repository, without express consent.***

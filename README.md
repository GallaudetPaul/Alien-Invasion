# 👾 Alien Invasion
A classic-style 2D space shooter game written in Python using the pygame library. You control a spaceship and shoot down waves of aliens before they reach the bottom of the screen!

# 🚀 How to Run the Game (Mac Version)
Prerequisites:
- Python 3.7 or newer
- pygame installed (version 2.x recommended)

How to Install:
Clone or download the project files using Terminal
1. $ git clone https://github.com/GallaudetPaul/Alien-Invasion.git
2. $ cd Alien-Invasion

How to Run:
Navigate to a folder of your choice in Terminal

1. $ ls
2. $ cd <fileName>
3. $ python alien_invasion.py

# 🎮 Controls
- Left Arrow / Right Arrow – Move the ship left/right
- Spacebar – Fire bullets
- Q – Quit the game
- Mouse Click – Click "Play" to start or restart the game

# ✅ Features Implemented
- Explosive animation
- Ship bullet animation
- Different mages for the background, ship, and aliens
- Ship that moves smoothly left and right
- Bullet firing with limit to prevent spam
- Alien fleet generation that moves and descends
- Bullet-alien collision detection
- Game stats tracking (score, high score, lives, level)
- Scoreboard rendering to display game info
- Play button for starting/restarting the game
- Game over state when lives reach zero
- Level system that increases difficulty after each wave
- Save/load scores to a file without identifying who set the records

# 🧠 Design Choices
- Object-Oriented Structure: The game is modular and split across classes:
  	- Ship handles the player-controlled spaceship.
  	- Alien manages the alien enemies.
  	- Bullet is for player bullets.
  	- Settings controls all game configuration (speed, limits, sizes).
  	- GameStats tracks lives, score, and levels.
  	- Scoreboard visually shows game stats.
  	- Button manages the UI button ("Play").
  	- Explosion manages explosive animation
  	- Alien Formation handles waves/leveling formations
  	- Powerup is for dropping power up effects
  	- Alien Bullet is responsible for firing bullets to the ship
- Progressive Difficulty: Alien speed and difficulty increase as you advance to higher levels.
- Collision Detection: Implemented using pygame.sprite.groupcollide for bullets and aliens.
- Multiple Alien Types: You can expand the game by using different images and behaviors for each alien type.
- Visual Feedback: The game background, ship, and alien sprites can be customized using .png images.

# 💡 Ideas for Future Improvement
- Sound effects and music
- Power-ups and multiple weapon types
- Pause and resume functionality
- Save/load high score to a file WITH names

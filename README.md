DANGER DAVE: RECHARGED
Game Changes and Features Documentation
PAGE 1 – INTRODUCTION AND CORE GAME IMPROVEMENTS
Danger Dave: Recharged is a modernized version of the classic Dangerous Dave-style platform game. The main objective of the project was to retain the basic platform-adventure gameplay while improving the graphics, controls, gameplay mechanics, characters, levels, and overall user experience. The new version introduces modern visual effects, physics-based movement, multiple characters, collectibles, enemies, combat, health, scoring, and a starting tutorial.
1. Modernized Graphics
The game was redesigned with a modern visual appearance instead of a simple traditional platform-game layout. Gradient backgrounds, atmospheric effects, parallax mountains, glowing objects, modern UI panels, and particle effects were added. These improvements make the game visually more attractive and give it a more polished appearance.
2. Character Selection
The game now provides three playable characters:
•	Dave: Balanced movement and jumping abilities.
•	Maya: Faster and more agile character.
•	Rook: Slower but has stronger jumping ability.
The player can select a character from the main menu before starting the game. Each character has different movement characteristics, making character selection an additional gameplay feature.
3. Improved Character Movement
The character movement was modified after the initial version was found to be too fast. The movement speed was reduced to provide better control and more precise navigation.
The updated movement system includes:
•	Controlled horizontal movement
•	Acceleration and deceleration
•	Gravity
•	Jumping
•	Falling
•	Platform collision
•	Different movement speeds for different characters
This makes the gameplay smoother and easier to control.
4. Physics System
Basic physics were introduced to make the game more realistic. Gravity continuously affects the character, jumping produces upward velocity, and the player falls naturally when not standing on a platform. Horizontal acceleration and friction also improve the feeling of movement.
5. Starting Tutorial
A tutorial was added at the beginning of the game to help new players understand the controls and objectives.
The tutorial explains:
A/D or ←/→ – Move
W/↑/Space – Jump
F/J/Ctrl – Shoot
Collect crystals – Defeat enemies – Reach EXIT
This makes the game easier for first-time players to understand.
________________________________________
PAGE 2 – LEVELS, ENEMIES AND COMBAT
6. Three Game Levels
The game was expanded to include three levels, each with a different environment and increasing difficulty.
Level 1 – Training Grounds
This is the introductory level. It contains the tutorial and teaches the player basic movement, jumping, collecting objects, fighting enemies, and reaching the exit. Platforms, spikes, crystals, and enemies are included.
Level 2 – Crystal Caverns
This level introduces more challenging platform arrangements and additional hazards. The player must collect at least six crystals before being allowed to escape through the exit. More enemies and obstacles are introduced compared with the first level.
Level 3 – Sky Fortress
This is the final and most challenging level. It contains a larger platform layout, additional enemies, hazards, and collectibles. The player must navigate through the fortress and reach the final exit to complete the game.
7. Enemy System
Enemies were added to make the gameplay more challenging and interactive. Enemies move around platforms and patrol their areas. They can damage the player when touched.
The player has two methods of defeating enemies:
1.	Jump on the enemy.
2.	Shoot the enemy using the gun.
This gives the player more freedom when dealing with obstacles.
8. Gun and Shooting System
A gun-based combat system was added to the game. The player can shoot enemies using:
F / J / Ctrl
When the player shoots, a bullet travels in the direction the character is facing. Bullets detect collisions with enemies and destroy them when they make contact.
The shooting system also includes:
•	Bullet movement
•	Bullet lifetime
•	Enemy collision detection
•	Shooting effects
•	Enemy destruction
•	Score rewards
Defeating an enemy by shooting provides 75 points, while defeating an enemy by jumping on it provides 100 points.
9. Collectible Crystals
Crystals were added as collectible objects throughout the levels.
When a player collects a crystal:
•	The crystal disappears.
•	The score increases by 25 points.
•	A particle effect is displayed.
•	The crystal counter in the HUD is updated.
The crystals provide an additional objective for players and encourage exploration of the levels.
10. Spikes and Environmental Hazards
Spikes were introduced as environmental obstacles. Touching a spike causes the player to take damage.
The player must carefully time jumps and movement to avoid these hazards while progressing through the levels.
11. Health and Lives
A health and life system was added to improve gameplay.
The player starts with 3 lives. Damage can occur from:
•	Enemy contact
•	Spikes
•	Falling from the level
After taking damage, the character becomes temporarily invulnerable. If all health is lost, a life is removed and the level restarts. When all lives are used, the Game Over screen is displayed.
________________________________________
PAGE 3 – SCORING, UI AND FINAL IMPROVEMENTS
12. Scoring System
A scoring system was implemented to track the player's performance.
Points are awarded for:
Action	Points
Collecting a crystal	25
Shooting an enemy	75
Stomping an enemy	100
Completing a level	Bonus
The score is displayed continuously during gameplay.
13. Level Exit and Progression
Each level contains an EXIT area. The player must reach the exit after completing the required objectives.
The progression is:
Training Grounds → Crystal Caverns → Sky Fortress → Mission Complete
In the Crystal Caverns level, the player must collect six crystals before the exit becomes usable.
After completing all three levels, the game displays a Mission Complete screen.
14. Modern HUD
A new heads-up display was added to provide important information during gameplay.
The HUD displays:
•	Game title
•	Current score
•	Remaining lives
•	Current level
•	Level name
•	Crystal count
•	Shooting controls
This allows players to monitor their progress without leaving the gameplay screen.
15. Particle and Visual Effects
Particle effects were added to provide immediate visual feedback.
Effects are displayed when:
•	Shooting
•	Defeating enemies
•	Collecting crystals
•	Taking damage
Glowing effects are also used for crystals and bullets to improve visibility.
16. Mobile and Keyboard Controls
The game supports both keyboard and touch-based controls.
Keyboard Controls
•	A / Left Arrow: Move left
•	D / Right Arrow: Move right
•	W / Up Arrow / Space: Jump
•	F / J / Ctrl: Shoot
•	Enter: Start or restart
•	Left / Right Arrow: Select character
Touch Controls
On touch-supported devices, on-screen buttons are provided for:
•	Moving left
•	Moving right
•	Jumping
This allows the game to be played on different types of devices.
17. Game Screens
The game includes several screens:
Main Menu
Contains the game title, character selection, character descriptions, controls, and start instructions.
Gameplay Screen
Displays the player, platforms, enemies, crystals, hazards, exit, score, lives, and level information.
Game Over Screen
Appears when all lives are lost and provides an option to restart the game.
Mission Complete Screen
Appears after completing all three levels and displays the final score.
18. Technical Implementation
The game was developed as a single browser-based HTML application using:
•	HTML – Game structure
•	CSS – Interface and visual styling
•	JavaScript – Game logic, physics, controls, enemies, shooting, scoring, and level management
•	HTML5 Canvas – Game rendering and animation
The game does not require a database, backend server, or external game engine. It can be opened directly in a modern web browser.
19. Final Outcome
The final Danger Dave: Recharged version provides a significantly improved gameplay experience compared with the basic original concept. The major additions include three characters, three levels, controlled movement speed, physics, tutorial support, gun-based combat, enemies, collectibles, hazards, scoring, health, lives, modern graphics, particle effects, level progression, and mobile controls.
These changes make the game more interactive, challenging, visually appealing, and suitable for demonstrating a modern browser-based platform game project.


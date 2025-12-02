## This project named "Sky Adventure" has been prepared for the CSE423: Computer Graphics course.

## Functionalities
The player controls a plane using arrow keys to move and mouse clicks to adjust speed while avoiding obstacles and collecting rewards. Initially, the plane's health is set to 100 HP at the start of the game. The goal is to survive, score points, and complete adventure levels before health runs out. Here's how health decreases:

- **Obstacle hits:** Obstacles appear in the plane's path and must be avoided to prevent damage. Colliding with them reduces the plane's health. Each collision costs 10 HP. However, it checks if the plane is in Power Mode and reduces health by only 5 HP in that case.
- **Rain:** While rain is active, health drains by 0.1 HP per frame (≈ 3 HP/second at ~30 FPS).
- **Health reaching 0 ends the game.**

## Collectibles
Collectibles increase the player's score when picked up, helping to achieve a higher total. They appear along the flight path and increase the player's score when collected. The more collectibles gathered, the higher the final score.

## Adventure Level
There will be two Adventure Levels:

- **Obstacle Run:** Obstacle Run Level is the main adventure mode where the plane continuously moves forward, and the player navigates through a field of obstacles, avoiding collisions while collecting items to score points and survive as long as possible.

- **Rapid Reward:** Rapid Rewards is a special adventure mode where the plane speeds up, and the player collects a large number of items appearing along the path to quickly increase their score while obstacles are temporarily cleared. The special feature of Rapid Rewards is the increased plane speed and abundant collectibles, allowing the player to earn points rapidly without worrying about obstacles.

## Mode
There will be two modes:

- **Power Mode:** Power Mode allows the player to shoot weapons from the plane, destroying obstacles in the path. Each shot slightly reduces the plane's health, 1 HP for every 20 shots, so it must be used strategically.

- **Ghost Mode:** As rain damages the plane, Ghost Mode makes the plane invulnerable to rain, preventing the health from decreasing by the usual 0.1 HP per frame during rain. This allows the player to focus on collecting items and avoiding obstacles without worrying about rain damage.

## First Person Perspective
First-person perspective mode is a camera view that places the player's viewpoint directly inside the cockpit, giving them the illusion of seeing the sky through the pilot's eyes. This mode provides an immersive experience by hiding the player's plane and changing the camera's position to a point slightly in front of the cockpit.

## Third Person Perspective
The game features a third-person perspective, with the camera positioned behind and above the plane, allowing the player to see the plane, obstacles, and collectibles while navigating through the environment.

## Player Control

### Keyboard Controls:
- **Arrow Up:** Tilt the plane upward (pitch up)
- **Arrow Down:** Tilt the plane downward (pitch down)
- **Arrow Left:** Move the plane left
- **Arrow Right:** Move the plane right
- **'U' and 'u':** Move the camera up
- **'D' and 'd':** Move the camera down
- **'L' and 'l':** Move the camera left
- **'R' and 'r':** Move the camera right
- **'S' and 's':** To restart the game
- **'F' and 'f':** To enable and disable first-person perspective mode
- **'P' and 'p':** Toggle Power Mode (enables shooting)
- **'G' and 'g':** Toggle Ghost Mode (only active during rain)
- **Spacebar:** Fire a weapon when Power Mode is ON
- **Esc:** Exit the game

### Mouse Controls:
- **Left Click:** Increase plane speed
- **Right Click:** Decrease plane speed

## Game Over
The "Game Over" feature is triggered when the plane's health drops to zero, bringing the flight to a decisive end. When this happens, all player controls become unresponsive and the plane stops moving forward. The screen then prominently displays a "GAME OVER" message, along with the player's final score, effectively concluding the current playthrough.


https://github.com/user-attachments/assets/dbafa797-75d6-4707-9bb2-8acfa3e6ec83





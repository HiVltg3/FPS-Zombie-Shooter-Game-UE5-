
# Architecture Overview

## Game Architecture

The game follows a **modular architecture** using Unreal Engine 5, allowing for flexible and scalable development. The architecture consists of several key components:

1. **PlayerController**: Handles the player's input and actions, translating them into movement, aiming, and shooting behaviors.
2. **AIController**: Manages zombie behavior, including movement, attack patterns, and targeting the player.
3. **GameMode**: Defines the game rules, victory conditions, and overall gameplay mechanics.
4. **HUD**: Displays essential information such as health, ammo, time, and mission objectives.
5. **Level Design**: Modular level layouts with varied environments and objectives.

### Key Systems

- **AI Behavior**: AI is driven by Behavior Trees, ensuring dynamic and intelligent actions by zombies.
- **Raycasting**: Used for precise shooting detection and collision handling.
- **Resource Management**: Implements health and ammo systems with limited resources to enhance the survival challenge.

### System Diagram
![Architecture Diagram](./path/to/architecture-diagram.png)  <!-- Replace with actual path -->

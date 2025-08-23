
# Technical Overview

## Game Engine: Unreal Engine 5

Unreal Engine 5 is used for its advanced capabilities in rendering, physics, and AI. The following features are utilized in the development:

- **Blueprints**: Visual scripting for gameplay mechanics, AI behavior, and user interfaces.
- **Nanite**: Provides high-fidelity 3D models and real-time rendering with millions of polygons.
- **Raycasting**: For shooting detection and collision, ensuring precise gameplay interactions.
- **Behavior Trees**: For AI logic, making zombies act intelligently based on player location and game state.
- **NavMesh**: For AI pathfinding, helping zombies navigate complex environments.

## Game Features Breakdown

### Player Movement
- WASD for movement, mouse for aiming and shooting.
- Smooth animations for walking, aiming, and firing, controlled by an **Animation State Machine**.

### Combat System
- Raycasting for shooting mechanics.
- Weapon recoil, ammo management, and reloading systems.
- AI enemies that follow, attack, and react to the player using **Behavior Trees** and **Blackboards**.

### Resource Management
- Health and ammo bars displayed on the HUD.
- Players collect resources and manage them to survive against zombies.

### AI
- **NavMesh** for pathfinding.
- **Behavior Trees** for zombie actions such as patrolling, following the player, and attacking.

## Performance Optimizations
- Using **Nanite** for high-quality 3D assets with minimal performance impact.
- Optimized AI pathfinding to reduce CPU usage.

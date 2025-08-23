
# Zombie Game Based on Unreal Engine 5

**Note**: This project was originally developed as part of my **graduation project**. Since it has been some time since the completion, I'm uploading it to **GitHub** purely for **showcase purposes**.

## Project Overview

This project involves the design and development of a **First-Person Shooter (FPS) Zombie Game** set in a post-apocalyptic world. Using **Unreal Engine 5**, the game offers **high-quality graphics**, **immersive sound effects**, and **AI-driven enemies**. Players take the role of survivors who must navigate levels filled with zombies, use strategic resource management, and fight to stay alive.

## Game Features

- **First-Person Perspective**: The player experiences the game through the eyes of the character.
- **Zombie AI**: Advanced **AI behavior trees** drive the actions of zombies, including random movement, attack, and following the player.
- **Resource Management**: Players manage health, ammunition, and resources as they fight through levels.
- **Dynamic Levels**: Levels are designed with escalating difficulty, unlocking new challenges as players progress.
- **Raycasting Mechanics**: Utilized for weapon firing and collision handling.
- **Visual and Audio Effects**: High-quality **Nanite**-based assets for realistic graphics, along with dynamic sound design.

## Technologies Used

- **Unreal Engine 5** for all game development (rendering, physics, etc.).
- **Blueprints**: Unreal’s visual scripting tool used for gameplay mechanics, AI behaviors, and UI.
- **AI Behavior Trees** for zombie actions.
- **Nanite** technology for real-time 3D model rendering with millions of polygons.

## Installation and Setup

### Prerequisites
- **Unreal Engine 5** installed
- **Visual Studio** (with C++ support)

### Steps to Run

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/zombie-game.git
    cd zombie-game
    ```

2. **Open the project in Unreal Engine 5**:
    - Launch Unreal Engine 5.
    - Open the `ZombieGame.uproject` file.

3. **Build the project**:
    - If any dependencies are missing, Unreal Engine will prompt you to install them.
    - Click **Build** to compile the project.

4. **Run the game**:
    - After the build is complete, press **Play** to run the game.

## Project Structure

Here’s an overview of the project directory structure:

```
zombie-game/
├── Assets/                    # 3D models, textures, and sound assets
├── Blueprints/                # Game logic and AI behaviors
├── Config/                    # Game configuration files (e.g., input mappings)
├── Content/                   # Game content (maps, materials, etc.)
├── Docs/                      # Documentation (this README, technical diagrams, etc.)
├── Source/                    # C++ source code
│   ├── ZombieGame/            # Main game logic
│   ├── ZombieGameEditor/      # Editor functionality
│   └── ZombieGameAI/          # AI behavior code
└── ZombieGame.uproject        # Unreal Engine project file
```

### Directories Explained:

- **Assets**: Contains all external game resources such as models, textures, and audio files.
- **Blueprints**: Unreal’s **visual scripting** for game mechanics, including player movement, shooting mechanics, and zombie AI.
- **Config**: Stores settings and preferences for input mapping and other configurations.
- **Content**: Holds Unreal Engine content like levels, materials, and particle effects.
- **Source**: Source code written in **C++** for game logic, AI, and custom features.

## Gameplay Instructions

1. **Start the Game**: Press **Play** after setting up the game.
2. **Movement**: Use **W, A, S, D** to move, **Mouse** to look around.
3. **Shooting**: Press **Left Mouse Button** to shoot. Use **Right Mouse Button** to aim.
4. **Inventory**: Press **I** to check your inventory.
5. **Objective**: Survive as long as you can and complete the level by defeating all zombies.

## Testing

The game underwent extensive testing, including:

- **Unit Testing**: Testing individual components like weapons, AI, and UI.
- **Integration Testing**: Ensuring the game components work together correctly.
- **AI Logic Testing**: Verifying AI pathfinding, decision-making, and combat strategies.
- **Performance Testing**: Ensuring smooth gameplay even with many on-screen zombies.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more information.

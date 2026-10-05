# ShooterSam

ShooterSam is an Unreal Engine 5 project focused on a fast-paced action and shooter prototype. The repository includes a collection of gameplay variants and level prototypes built around movement, combat, enemies, and interactive systems.

## Overview

This project is organized as an Unreal Engine game project with:

- C++ gameplay logic and module configuration
- Multiple gameplay variants for different playstyles
- Input mappings and touch support
- Prototype levels and interactable objects
- Character and AI assets for combat and platforming scenarios

The project is configured for Unreal Engine 5.6 and uses the `ShooterSam` runtime module.

## Project Structure

```text
ShooterSam/
├── Config/                   # Engine and project configuration files
├── Content/                  # Unreal assets and levels
│   ├── Characters/
│   ├── Input/
│   ├── LevelPrototyping/
│   ├── ThirdPerson/
│   ├── Variant_Combat/
│   ├── Variant_Platforming/
│   ├── Variant_SideScrolling/
│   └── ...
├── Source/
│   └── ShooterSam/
│       ├── ShooterSam.Build.cs
│       └── ...
├── ShooterSam.uproject
├── .gitignore
├── .gitattributes
├── .vsconfig
└── README.md
```

## Gameplay Variants

### Combat Variant
- Enemy AI and controllers
- Combat character logic
- Health/damage interactions
- Damageable props, checkpoints, and lava hazards
- Camera shake and UI feedback

### Platforming Variant
- Dash movement and jump mechanics
- Jump pads and interactive movement systems
- Platforming-focused player controller and animation support

### Side-Scrolling Variant
- Side-scrolling character controls
- Pickup and moving platform interactions
- NPC AI and level structure

### Prototyping Assets
- Doors, jump pads, targets, ramps, and generic environment props
- Reusable materials, meshes, and level building blocks

## Requirements

- Unreal Engine 5.6
- Visual Studio 2022 with C++ game development tools
- Windows environment recommended for this project
- Epic Games Launcher for engine installation and project setup

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/SupremeX15/ShooterSam.git
```

2. Open `ShooterSam.uproject` with Unreal Engine 5.6.

3. If prompted, allow Unreal Engine to rebuild project files and dependencies.

4. If building from source in Visual Studio, generate project files as needed and compile the project.

5. Launch the editor and open the available maps or gameplay variants.

## Development Notes

This repository contains both Blueprint-based assets and C++ modules. The project is structured to support experimentation with multiple gameplay patterns in one codebase.

The main module is named `ShooterSam`, and its build configuration includes dependencies such as:

- Core
- CoreUObject
- Engine
- InputCore
- EnhancedInput
- AIModule
- UMG
- Slate
- StateTreeModule
- GameplayStateTreeModule

## Contributing

This project appears to be a personal Unreal Engine prototype or learning project. Contributions are welcome if you want to expand mechanics, polish gameplay, or clean up the project structure.

## License

No explicit license file is present in the repository. If you plan to reuse or redistribute the project, check with the repository owner before using it in other projects.

## Author

SupremeX15

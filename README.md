# Wolf3D Game Project
## Project Overview

Wolf3D is a first-person 3D game engine inspired by the classic Wolfenstein 3D. This project is built in C using the CSFML library (Simple and Fast Multimedia Library for C) to handle graphics, audio, and input.

## Features

- **3D Navigation**: First-person exploration with raycasting technique
- **Weapon System**: Animated weapon with attack mechanics
- **Movement Mechanics**: Walking and dashing abilities
- **Comprehensive Settings System**:
  - Game settings (mouse sensitivity)
  - Controls customization (fully rebindable keys)
  - Video settings (display mode, FPS)
  - Audio settings (master and music volume)
- **Polished UI**: Menu system with intuitive navigation

## Building and Running

### Prerequisites

- GCC compiler
- CSFML libraries (graphics, window, system, audio)
- Make

### Compilation

```bash
make
```

The compilation will generate the `wolf3d` executable.

### Running the Game

```bash
./wolf3d
```

## Controls

The game features fully customizable controls. Default keybinds include:
- Movement: Arrow keys or WASD
- Attack: Left mouse button
- Settings: ESC key to access

## Settings

The settings menu is divided into four sections:

1. **Game Settings**:
   - Mouse sensitivity adjustment (1-10)

2. **Controls Settings**:
   - Rebind movement keys (forward, backward, left, right)
   - Rebind rotation keys

3. **Video Settings**:
   - Display mode selection
   - FPS configuration

4. **Audio Settings**:
   - Master volume control
   - Music volume control

## Project Structure

- src: Source code files organized by functionality
- include: Header files
- assets: Game graphics and UI elements
- fonts: Custom font files
- music_theme: Background music tracks
- sounds_effects: Game sound effects
- map.txt: Level design file

## Development

This project uses a modular approach with separate components for:
- Event handling
- Settings management
- UI rendering
- Game logic
- Audio management

## Credits

Developed as an EPITECH project, 2025 by Gabriel-Spanneut--Peressutti

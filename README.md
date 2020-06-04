# VRBasics
VR Basic Movement 

Simple template game to make a locomotion movement on Oculus Quest

# Version

Unreal Engine 4 - 4.24.3

# Style and Code Standard

- https://github.com/Allar/ue4-style-guide#0.1
- https://docs.unrealengine.com/en-US/Programming/Development/CodingStandard/index.html#exampleformatting

## Inputs

![Screen Recording 2020-04-11 at 4 37 32 PM_2](https://i0.wp.com/vrespawn.com/wp-content/uploads/2019/05/Oculus-touch-controllers-1.png?w=696&ssl=1)

- **Move joystick mode:** Uses the left or right thumbsticks
- **Move Teleport mode:** Press thumbsticks and after release it, the character will be teleported
- **Open 3D Widget:** Use the Right Controller and press buttons **A** or **B**
- **Interact Widget:** Press Right Trigger


## How to Install the game
- Download the apk file from here https://github.com/ingridwarrior2901/VRBasics/releases/download/v0.1/Android_ASTC.zip
- And Finally Install it via SideQuest https://sidequestvr.com/setup-howto 

## Game Architecture

All the gameplay was made on C++ scripting, the blueprints is used only on the UI and inputs that call game logic.

## Dependencies

- Oculus Plugin: https://developer.oculus.com/documentation/unreal/unreal-getting-started-guide/


## Gameplay

#### Teleport

TBD

#### Joystick

TBD

## Folder Structure

```
.
├── Config
│   ├── DefaultEditor.ini
│   ├── DefaultEngine.ini
│   ├── DefaultGame.ini
│   └── DefaultInput.ini
├── Content
│   ├── Collections
│   ├── Developers
│   │   └── cris
│   └── VRBasicsCore
│       ├── Characters
│       ├── Core
│       ├── Maps
│       ├── Materials
│       └── UI
├── README.md
├── Source
│   ├── VRBasics
│   │   ├── Private
│   │   ├── Public
│   │   ├── VRBasics.Build.cs
│   │   ├── VRBasics.cpp
│   │   ├── VRBasics.h
│   │   ├── VRBasicsGameModeBase.cpp
│   │   └── VRBasicsGameModeBase.h
│   ├── VRBasics.Target.cs
│   └── VRBasicsEditor.Target.cs
├── VRBasics.uproject

```

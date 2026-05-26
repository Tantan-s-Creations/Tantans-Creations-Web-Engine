# Tantan's Creations Web Engine v1.9

## Description: 
Tantan's Creations Web Engine is a HTML + WebGL game engine supported with 3D + 2D games. Engine was developed by Tantan's Creations.

# Features
## Core Engine
2D & 3D Game Creation - Seamlessly switch between 2D sprite-based and 3D mesh-based development
Entity Component System (ECS) - High-performance data-oriented architecture with OOP editor wrappers
Software Renderer - Real-time 3D viewport with lighting, shadows, and gizmos
Asset Pipeline - Import OBJ, FBX, PNG, JPG, WAV, MP3, CS, JS, and more
Prefab System - Reusable entity templates with override tracking
## Scripting
Dual Language Support - Write in C# (transpiled to JS) or native JavaScript
Unity-Compatible API - Familiar MonoBehaviour lifecycle (Start, Update, FixedUpdate, OnCollisionEnter)
In-Engine Editor - Syntax highlighting, line numbers, and multi-tab support
Live Compilation - Scripts compile in-memory for instant playtesting
## Editor
Dockable Workspace - Customizable panel layout (Hierarchy, Inspector, Project, Console, Script Editor)
Scene Viewport - Orbit, pan, zoom camera controls with entity selection
Transform Gizmos - Visual XYZ axis manipulation for selected objects
Project Settings - Unity-style Player, Display, Physics, Input, Audio, Scripting, and Build settings
Console - Filterable log output with Info, Warning, Error, and Script categories
## Export & Build
Single HTML Export - One self-contained .html file with all assets embedded
Standard Web Export - Separate JS and data files for hosting
Three.js Runtime - Exported games run on Three.js with WebGL 2.0
Progressive Web App - Optional service worker and manifest (future)
Asset Optimization - Texture compression, mesh optimization, and dead code elimination

## Requierments:
Python 3.8 or higher
Windows 10/11, Linux, or macOS
PIL (Pillow) and NumPy (usually included with Python)

---------------------------------------------------------------

# Creating Your First Game
## 1. New Project
File > New Project

Name your project and choose a location

## 2. Create a Scene
GameObject > Create Empty (or Cube, Sprite, Light, Camera)

Use the Inspector to set position, rotation, scale

## 3. Add a Script
Select your player entity

Inspector > Add Component > Script

Choose JavaScript or C#

Write your game logic

## 4. Test in Play Mode
Click the Play button (or press F5)

Test your game in the viewport

Click Stop to return to editing

## 5. Export to HTML
Click "Build HTML" in the toolbar

Find your game in the `Build/` folder

Open `index.html` in any browser

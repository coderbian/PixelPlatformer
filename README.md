# PixelPlatformer

A 2D Pixel Art Platformer game built with Unity.

## 📁 Project Structure

```
PixelPlatformer/
├── Assets/                          # Game assets and resources
│   ├── kenney_pixel-platformer/     # Kenney pixel art assets
│   │   ├── Construct 3/             # Construct 3 project files
│   │   ├── Tiled/                   # Tiled map editor files
│   │   │   ├── tilemap-example-a.tmx
│   │   │   ├── tilemap-example-b.tmx
│   │   │   └── tilesheet-tiles.tsx
│   │   ├── Tilemap/                 # Tilemap sprite sheets
│   │   │   ├── tilemap-backgrounds.png
│   │   │   ├── tilemap-backgrounds_packed.png
│   │   │   ├── tilemap-characters.png
│   │   │   ├── tilemap-characters_packed.png
│   │   │   ├── tilemap.png
│   │   │   └── tilemap_packed.png
│   │   ├── Tiles/                   # Individual tile sprites (231 tiles)
│   │   │   └── tile_*.png
│   │   ├── License.txt              # Asset license information
│   │   ├── Preview.png              # Asset preview images
│   │   ├── SampleA.png
│   │   └── SampleB.png
│   └── Scenes/                      # Unity scenes
│       └── SampleScene.unity
│
├── Packages/                        # Unity Package Manager
│   ├── manifest.json                # Package dependencies
│   └── packages-lock.json           # Locked package versions
│
├── ProjectSettings/                 # Unity project settings
│   ├── AudioManager.asset
│   ├── DynamicsManager.asset
│   ├── EditorBuildSettings.asset
│   ├── GraphicsSettings.asset
│   ├── InputManager.asset
│   ├── Physics2DSettings.asset
│   ├── ProjectSettings.asset
│   └── ... (other settings)
│
├── .vscode/                         # VSCode/Cursor configuration
│   ├── settings.json                # Editor settings
│   ├── launch.json                  # Debug configuration
│   └── extensions.json              # Recommended extensions
│
├── .gitignore                       # Git ignore rules
├── README.md                        # This file
└── PixelPlatformer.sln              # Visual Studio solution

# Excluded from Git (auto-generated):
├── Library/                         # Unity cache (DO NOT COMMIT)
├── Temp/                            # Temporary files (DO NOT COMMIT)
├── Logs/                            # Log files (DO NOT COMMIT)
├── UserSettings/                    # User-specific settings (DO NOT COMMIT)
└── obj/                             # Build output (DO NOT COMMIT)
```

## 🎮 About

This is a 2D platformer game project using pixel art assets from [Kenney](https://kenney.nl/).

## 🛠️ Built With

- **Unity** - Game Engine
- **C#** - Programming Language
- **Kenney Pixel Platformer Pack** - Art Assets

## 📦 Assets

This project uses the **Kenney Pixel Platformer** asset pack, which includes:
- 231 individual tile sprites
- Multiple tilemap sprite sheets (tiles, characters, backgrounds)
- Example tilemaps for Tiled editor
- Free to use under Kenney's license

## 🚀 Getting Started

### Prerequisites

- Unity (compatible version specified in ProjectSettings/ProjectVersion.txt)
- Git with SSH configured for GitHub

### Installation

1. Clone the repository:
```bash
git clone git@github.com:coderbian/PixelPlatformer.git
```

2. Open the project in Unity:
   - Launch Unity Hub
   - Click "Open" or "Add"
   - Navigate to the cloned folder
   - Select the `PixelPlatformer` folder

3. Wait for Unity to import all assets

### Development Setup

For the best development experience with Cursor/VSCode:

1. Install recommended extensions (see `.vscode/extensions.json`)
2. Restart Cursor/VSCode after opening the project
3. Git integration will track changes automatically

## 📝 Git Workflow

```bash
# Check status
git status

# Stage changes
git add .

# Commit
git commit -m "Your commit message"

# Push to GitHub
git push origin main
```

## 📄 License

Project structure and code: [Your License Here]

Kenney Pixel Platformer Assets: See `Assets/kenney_pixel-platformer/License.txt`

## 🔗 Links

- **Repository**: [github.com/coderbian/PixelPlatformer](https://github.com/coderbian/PixelPlatformer)
- **Kenney Assets**: [kenney.nl](https://kenney.nl/)

## 👤 Author

**coderbian**

---

Made with ❤️ using Unity and Kenney's amazing pixel art assets
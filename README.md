# Stealth Gameplay

A stealth gameplay prototype built in Unreal Engine: a player character, AI guards, throwable items and magic powers.

- **Engine:** Unreal Engine 5.6
- **Built with:** Blueprint
- **Plugins:** Motion Warping

## What's in this repo

This repo holds the project's own work: Blueprints, levels, input and config.

| Folder | Contents |
| --- | --- |
| `Content/stealth_gameplay_system/for_player_character` | Player character and animations |
| `Content/stealth_gameplay_system/ai_characer` | AI character and its animations |
| `Content/stealth_gameplay_system/item_throwing_tools` | Throwable items: actors, assets and data |
| `Content/stealth_gameplay_system/fractur_actor` | Fracturable actors |
| `Content/stealth_gameplay_system/UI` | Interface widgets |
| `Content/stealth_gameplay_system/INPUT` | Input actions and mapping contexts |
| `Content/stealth_gameplay_system/world` | Maps, world actors, materials, sounds and meshes |
| `Content/BluePrints` | Enemy Blueprint and powers (fire, ice, lightning, magma, dark stone) |
| `Config` | Project settings |

## Asset packs you need to add

The third-party asset packs are not included, because their licences do not allow republishing the raw files. The full project is about 6.6 GB with them. To open the levels as intended, add these packs to the project from Fab so they land in `Content/`:

- **Paragon characters:** Gideon, Kwang
- **VFX and animation:** Free Magic, Mixed Magic VFX Pack, Combat Magic Anims, Vefects, Spline VFX

Without them the project still opens, and the Blueprints can be read, but characters and effects from the packs show as missing.

## Open the project

1. Install Unreal Engine 5.6 and [Git LFS](https://git-lfs.com).
2. Clone the repo. The `.uasset` and `.umap` files are stored with Git LFS.
3. Add the packs listed above.
4. Open `StealthGameplay.uproject`.

## Author

Ravi Rajan · [Portfolio](https://ravi-rajan-portfolio.vercel.app)

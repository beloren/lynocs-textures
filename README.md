# Lynocs Stylized Textures

536 stylized, tileable textures (diffuse/colour maps, **1024×1024 JPEG**) in 50 groups. Every file has a direct public URL, so you can use one texture without downloading the whole pack.

![overview](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/overview.jpg)

## For AI assistants: how to use this

1. Read **[`index.json`](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/index.json)**: every texture with its `id`, average colour `avg` and direct `url`.
2. To choose visually, open a group's contact sheet: `https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/<group>.jpg` (labels under each tile are the texture names).
3. Fetch only the textures you need by URL:
   - CDN (fast, cached): `https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/textures/<group>/<name>.jpg`
   - GitHub raw (fallback): `https://raw.githubusercontent.com/beloren/lynocs-textures/main/textures/<group>/<name>.jpg`
4. Names: `<n>.jpg` is a texture; in `roof` and `water`, `<n>-<colour>.jpg` is a recoloured copy of `<n>.jpg`.

Example: `https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/textures/wood-planks/3.jpg`, `https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/textures/metal/5.jpg`.

Tiling in CSS:
```css
.surface { background: url("https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/textures/grass/3.jpg") repeat; background-size: 256px; }
```

## Groups

| Group | id | Textures | Preview |
|---|---|---|---|
| Alien Floor | `alien-floor` | 23 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/alien-floor.jpg) |
| Alien Planet | `alien-planet` | 17 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/alien-planet.jpg) |
| Beach | `beach` | 7 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/beach.jpg) |
| Burned Earth | `burned-earth` | 3 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/burned-earth.jpg) |
| Bush Hedge | `bush-hedge` | 10 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/bush-hedge.jpg) |
| Cave Floor | `cave-floor` | 13 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/cave-floor.jpg) |
| Cave Wall | `cave-wall` | 10 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/cave-wall.jpg) |
| Cobblestone | `cobblestone` | 7 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/cobblestone.jpg) |
| Cracked Indoor Walls | `cracked-indoor-walls` | 5 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/cracked-indoor-walls.jpg) |
| Damaged Parquet | `damaged-parquet` | 10 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/damaged-parquet.jpg) |
| Damaged Stone Wall | `damaged-stone-wall` | 5 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/damaged-stone-wall.jpg) |
| Desert | `desert` | 5 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/desert.jpg) |
| Fall Ground | `fall-ground` | 6 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/fall-ground.jpg) |
| Fire Grass | `fire-grass` | 2 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/fire-grass.jpg) |
| Flesh | `flesh` | 8 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/flesh.jpg) |
| Floor | `floor` | 20 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/floor.jpg) |
| Fur | `fur` | 6 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/fur.jpg) |
| Grass | `grass` | 18 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/grass.jpg) |
| Groomed Snow | `groomed-snow` | 2 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/groomed-snow.jpg) |
| Ground | `ground` | 15 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/ground.jpg) |
| Hell | `hell` | 11 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/hell.jpg) |
| Horror Walls | `horror-walls` | 12 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/horror-walls.jpg) |
| Ice | `ice` | 6 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/ice.jpg) |
| Lava | `lava` | 11 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/lava.jpg) |
| Magical Forest | `magical-forest` | 4 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/magical-forest.jpg) |
| Magical Wood Planks | `magical-wood-planks` | 8 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/magical-wood-planks.jpg) |
| Metal | `metal` | 10 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/metal.jpg) |
| Metal Plates | `metal-plates` | 7 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/metal-plates.jpg) |
| Monster Skin | `monster-skin` | 15 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/monster-skin.jpg) |
| Mud | `mud` | 10 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/mud.jpg) |
| Mystical Ground | `mystical-ground` | 10 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/mystical-ground.jpg) |
| Pile of Gold | `pile-of-gold` | 4 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/pile-of-gold.jpg) |
| Roof | `roof` | 11 + 36 colour variants | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/roof.jpg) |
| Roots | `roots` | 13 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/roots.jpg) |
| Sand | `sand` | 10 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/sand.jpg) |
| Sci-Fi | `sci-fi` | 10 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/sci-fi.jpg) |
| Skull Floor | `skull-floor` | 4 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/skull-floor.jpg) |
| Snow | `snow` | 10 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/snow.jpg) |
| Snow Ground | `snow-ground` | 11 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/snow-ground.jpg) |
| Snow Roofs | `snow-roofs` | 8 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/snow-roofs.jpg) |
| Snowy Grass | `snowy-grass` | 6 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/snowy-grass.jpg) |
| Snowy Hedge Bush | `snowy-hedge-bush` | 6 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/snowy-hedge-bush.jpg) |
| Stone Wall | `stone-wall` | 15 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/stone-wall.jpg) |
| Swamp | `swamp` | 6 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/swamp.jpg) |
| Tiles | `tiles` | 6 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/tiles.jpg) |
| Tree Bark | `tree-bark` | 10 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/tree-bark.jpg) |
| Volcano | `volcano` | 8 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/volcano.jpg) |
| Wall with Plants | `wall-with-plants` | 11 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/wall-with-plants.jpg) |
| Water | `water` | 9 + 36 colour variants | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/water.jpg) |
| Wood Planks | `wood-planks` | 10 | [sheet](https://cdn.jsdelivr.net/gh/beloren/lynocs-textures@main/previews/wood-planks.jpg) |

## What is not here

The original pack also has AO, edge, height, metallic, normal and smoothness maps (BMP) for 3D. Only the diffuse maps are in this repo.

## License

[Texture Pack by Lynocs](https://lynocs.itch.io/texture-pack), marked **CC0 1.0**: free for private and commercial use, no attribution required (credit to Lynocs appreciated). The author asks that the textures not be resold as they are. The author states the textures were made AI-assisted. Files here were converted from the original PNG/BMP to JPEG (quality 86); no other changes.

# RTX High - Setup help

Everything you need to get **RTX High** running, step by step. If something goes wrong, check *Troubleshooting* at the end.

## What you need

- Minecraft **Bedrock Edition** 1.26.0 or newer (Windows, phone, console or a Bedrock server)
- Minecraft Bedrock on **Windows 10/11** with **ray tracing** support (NVIDIA RTX or AMD RX 6000 and newer)
- Minecraft **1.26.0 or newer**
- Ray tracing switched on: *Settings -> Video -> Graphics Mode: Ray Tracing*

## Install and start

1. Download **`RTX-High-v0.14.0-alpha.mcaddon`** from the [Releases page](../../releases) - or directly from this repository.
2. Open the file (double-click on Windows, or tap it on a phone/tablet). Minecraft starts and shows *Import started* / *Import successful*.
3. Create a new world or edit an existing one and open **Add-Ons**.
4. Under **Behavior Packs** activate this add-on's pack, then under **Resource Packs** activate the matching resource pack.
5. Start the world. (On a dedicated server, copy the two pack folders from the `.mcaddon` - it is a zip - into `behavior_packs` and `resource_packs` and list them in the world's pack files.)
6. If something does not show up, open the world's **Experiments** page and switch on **Beta APIs** and **Holiday Creator Features**, then reload the world.

## First start

1. Open the `.mcaddon` - Minecraft imports it.
2. Go to *Settings -> Global Resources* and activate **RTX High** (or activate it per world under *Resource Packs*).
3. Switch *Graphics Mode* to **Ray Tracing**. Without ray tracing the pack still loads, but reflections, relief and glow are not visible.

## Get the Dev Book (easter egg)

Place **9 logs** (any wood type) in all nine slots of a crafting table. The result is the **Dev Book**. Right-click it to open it like a real book: credits, a short description of this add-on, and the GitHub links. In creative mode you find it under *Equipment*.

## How to use it

- Nothing to configure: activate the pack, switch on ray tracing and look around. Dye leather armor to change the outfit.

## Troubleshooting

**Everything looks like the normal game**

Ray tracing is off or not supported by your graphics card. The PBR data only shows with *Graphics Mode: Ray Tracing*.

**Some blocks look blurry or low-res**

This is an early alpha at 128x - please report the block (name + screenshot) in the issues.

**Low FPS**

128x textures need VRAM. Lower the render distance or the ray tracing render distance.

**The pack does not import**

Make sure the file ends in `.mcaddon` (not `.zip`) and that Minecraft is up to date.

**The add-on does not do anything in my world**

Both the Behavior Pack **and** the Resource Pack must be active, and the world needs *Beta APIs* / *Holiday Creator Features* if your Minecraft version asks for them.

**I updated but nothing changed**

Remove the old pack version from the world's Add-Ons page (and from *Storage* -> *Behavior/Resource Packs*), then import again.

## Uninstall

Remove the packs from your world's Add-Ons page, and delete them under *Settings -> Storage -> Behavior Packs / Resource Packs*.

## Still stuck?

Open an **Issue** on this repository and tell me your Windows / Minecraft version and what you see (a screenshot helps).

---

Made by **dev:#2444** - [github.com/hash2444](https://github.com/hash2444)

# Scuffed-GTNH-Dark (Continued) — 2.9 Edition

**GT New Horizons: dark UI theme, updated for GTNH 2.9.0 (tested against 2.9.0-RC-2)**

> **This is not my own work.** I (**CapitaoBomba**, GitHub: [CptBomba](https://github.com/CptBomba)) only **updated and edited** this resource pack so it works with GTNH 2.9.
> All the original design and the vast majority of the textures belong to the original creator and the previous maintainer (see [Credits](#credits)).
>
> **Isto não é uma produção minha.** Eu (**CapitaoBomba**) apenas **atualizei e editei** este resource pack para funcionar no GTNH 2.9. Todo o design original e a grande maioria das texturas pertencem ao criador original e ao mantenedor anterior (veja os [Créditos](#credits)).

---

## Download

Grab the latest `.zip` from the **[Releases](https://github.com/CptBomba/Scuffed-GTNH-Dark-Continued/releases)** page and drop it into your `resourcepacks` folder.

Baixe o `.zip` mais recente na página **[Releases](https://github.com/CptBomba/Scuffed-GTNH-Dark-Continued/releases)** e coloque na pasta `resourcepacks`.

## Load order / Ordem dos packs

This pack must stay **above** any other pack that also changes GUI textures (Faithful, Unity, etc.), otherwise their textures win.

Este pack precisa ficar **acima** de qualquer outro pack que altere texturas de GUI (Faithful, Unity etc.), senão as texturas deles têm prioridade.

Recommended / recomendado:
1. Scuffed-GTNH-Dark-Continued (this pack)
2. Zedtech-New-Horizons
3. Unity IC2-Backport
4. Unity (or Faithful)

---

## What changed for 2.9 / O que mudou para a 2.9

Changes made by CapitaoBomba on top of the 2.8 version by Marneyy_:

- **Player inventory**: Hodgepodge 2.7 now swaps the vanilla inventory texture for `hodgepodge:textures/gui/inventory_new.png` (crafting grid moved). Added a dark version.
- **Backpack mod 2.6**: the player-inventory slots are drawn from a new region of `guiCombined.png` (they were invisible); dark backpack titles.
- **Simple Storage (ezstorage)**: new dark storage/crafting GUIs, side buttons and readable item counter.
- **Cosmetic Armor Reworked** (new in 2.9): dark cosmetic armor inventory.
- **GregTech ModularUI2 machines**: dark `item_standard` / `fluid_standard` / tank slots, popups, steam (bronze/steel) buttons, cover tabs resized to the new 20x20 layout, new prospector GUI size, Kubatech apiary and Intergalactic backgrounds.
- **More readable text**: light titles and text in GregTech and ModularUI2 themes (via `assets/gregtech/themes.json`), brighter ModularUI 1 text colours, white container titles for several mods.
- **ModularUI / ModularUI2**: new player/hotbar slot and context-menu textures, progress bars updated to the new 20x40 layout.
- **Baubles Expanded 2.2**, **BogoSorter**: dark unused bauble slots and sort buttons.
- **Cleanup**: removed outdated full copies of the Blood Magic and Adventure Backpack language files, which were overriding the 2.9 texts.
- New pack icon (same design, with a 2.9 badge) and description.
- **2.9 colour system (rc2.1)**: AE2, GregTech, NEI, Tinkers, EnderIO and others now read GUI colours from GTNHLib `color.resource.*` keys; the old lang colour keys are ignored. Added dark-theme overrides in `assets/gtnhlib/lang/en_US.lang` (fixes unreadable AE2 crafting status text).
- **AE2 2.9 (rc2.1)**: new icons in `states.png` (the pink squares in the crafting CPU list), 14 new AE2 GUIs, new network status bar and CPU selector line; new NEI and NEI Custom Diagram sprites.

---

## Credits

- **Original creator:** [**Flanisch**](https://github.com/Flanisch) (Discord: **@Albi**) — [Scuffed-GTNH-Dark](https://github.com/Flanisch/Scuffed-GTNH-Dark)
- **Previous maintainer (2.7 / 2.8 "Continued"):** **Marneyy_ / Kuliiuu** (Discord: **@marneyy_**) — [Kuliiuu/Scuffed-GTNH-Dark-Continued](https://github.com/Kuliiuu/Scuffed-GTNH-Dark-Continued); the new project is [Dark-GTNH-Reimagined](https://github.com/Kuliiuu/Dark-GTNH-Reimagined)
- **2.9 update and edits:** **CapitaoBomba** ([CptBomba](https://github.com/CptBomba))

This resource pack also uses and adapts assets from:

- [Unity](https://github.com/Unity-Resource-Pack/Unity/tree/1.7.10) by [CyanideX](https://github.com/CyanideX)
- [Zedtech-New-Horizons](https://github.com/FyreofShadow/zedtech-new-horizons) by [Zerrens](https://forum.industrial-craft.net/core/user/12229-zerrens/), [MCTian-mi](https://github.com/MCTian-mi) and [FyreofShadow](https://github.com/FyreofShadow)

The textures in this pack are recoloured or edited versions of the GUI textures of the mods in the GT New Horizons modpack. The original art belongs to the respective mod authors.

---

## License

This project is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/) (CC BY-NC-SA 4.0), the same license as the original pack. See [LICENSE.md](LICENSE.md).

- **Attribution:** keep the credits above when sharing or modifying it.
- **NonCommercial:** it may not be sold or used for commercial purposes.
- **ShareAlike:** modified versions must be released under the same license.

Este projeto usa a mesma licença do pack original (CC BY-NC-SA 4.0): mantenha os créditos, não use comercialmente e distribua versões modificadas sob a mesma licença.

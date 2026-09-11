# Shin-Yu-Gi-Oh-Forbidden-Memories

Shin Yu-Gi-Oh! Forbidden Memories version A is a soft rebalance mod designed to enhance the original Yu-Gi-Oh! Forbidden Memories experience while preserving its core identity.

The main goal of the mod is not to add new cards or radically change the original game, but rather to expand and rebalance its existing mechanics. The fusion system has been significantly expanded with new fusion paths and progression routes using only the original card pool, giving many previously underused cards new purposes and allowing a much wider variety of viable deck-building strategies.

The drop system has also been redesigned. Card drops no longer depend on POW/TEC results or duel ranks, removing the need to repeatedly pursue specific ranking strategies when farming cards. Instead, drops follow a unified rarity-based system intended to make progression more natural while maintaining the value of rare cards.

Opponent decks and progression have been rebalanced as well, with characters receiving improved decks in order to provide a greater and more consistent challenge throughout the game.

Several additional adjustments have been made to Fusion, Equip, Magic and Trap Cards, card costs, and other mechanics. However, the guiding principle remains the same throughout the project: expand what Forbidden Memories already offers rather than replace it.

In short, this mod aims to provide a more balanced, varied, challenging, and rewarding version of the original game without introducing new cards or abandoning the gameplay style that defines Forbidden Memories.

---

## Project Files

The project consists of three main files:

### 1. Guide

The **Guide** contains detailed information about the modifications introduced in Shin Yu-Gi-Oh! Forbidden Memories. It is highly recommended to read it before playing, as it explains the changes made to the original game and provides important information about the new progression system.

Among other things, the Guide includes:

- Changes to card drops and rarity;
- New and modified fusion possibilities;
- Changes to Equip, Magic, and Trap Cards;
- Card cost adjustments;
- Opponent and progression changes;
- Important information about obtaining cards, including the availability of card passwords at very low costs.

The Guide is intended to serve as the main reference for understanding the changes made by the mod.

### 2. XDelta Patch

The `.xdelta` file contains the modifications made to the original game.

The patch can be applied using the **xdelta-wasm online patcher**:

https://kotcrab.github.io/xdelta-wasm/

You will need to provide your own copy of the original game and apply the `.xdelta` patch to it.

> **Note:** The original game is not included with this project.

### 3. Card Finder

The **Card Finder** is a Python program included to make searching for card drops easier.

The program reads the drop tables provided with it and allows you to search for a card using either its **name or card number**. It then displays the available drop information for that card, making it unnecessary to manually search through the individual drop tables.

The drop tables used by the Card Finder are included together with the program and correspond to the current version of the mod.

> **Important:** As the project is updated, the **Guide, XDelta patch, and Card Finder/drop tables may also receive updates**. It is recommended to always use the files provided with the latest release.

# quest-base

A basis of quest classes and functions designed for use in a frontend interface

## Table of Contents

1. [Hierarchy and Terminology](#hierarchy)

## Hierarchy and Terminology <a name="hierarchy"></a>

### Hierarchy

- Dungeon
  - Floor
    - Room
      - Entity
        - Item
          - Armor
          - Consumable
        - Monster
          - Boss
          - Character

### Terminology

- **Armor** - an item that can be worn and unequipped by a monster to provide stat bonuses
- **Boss** - a monster with enhanced abilities, more complicated ai, or some other increased significance
- **Character** - a monster which is controlled by the player
- **Consumable** - an item that will alter the status of a the monster interacting with the item (e.g. status effects, increased stats)
- **Dungeon** - a collection of floors, monsters, items, and bosses which make up gameplay
- **Entity** - any item, monster, or interactable object present within a floor
- **Floor** - a subset level layer within a dungeon
- **Game** - a representation of all game global objects and functions
- **Item** - an entity that can be used by a monster or placed in an inventory
- **Monster** - an entity that can be controlled (whether by player or ai), can move, attack or engage in dialogue
- **Player** - the user playing the game through some form of input (keyboard, touchscreen)
- **Room** - a specified area present within a floor

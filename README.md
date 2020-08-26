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
        - Monster
          - Boss
          - Character

### Terminology

- **Boss** - a monster with enhanced abilities, more complicated ai, or some other increased significance
- **Character** - a monster which is controlled by the player
- **Dungeon** - a collection of floors, monsters, items, and bosses which make up gameplay
- **Entity** - any item, monster, or interactable object present within a floor
- **Floor** - a subset level layer within a dungeon
- **Item** - an entity that can be used by a monster or placed in an inventory
- **Monster** - an entity that can be controlled (whether by player or ai), can move, attack or engage in dialogue
- **Player** - the user playing the game through some form of input (keyboard, touchscreen)
- **Room** - a specified area present within a floor

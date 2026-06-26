# Realm of Echoes — World Content

Game world content for [realm-of-echoes-v2](https://github.com/AriesT/realm-of-echoes-v2).

## Structure

```
global/          — skills, monsters, factions, quests, dialogues, status effects, settings
zones/
  stone_ford/    — 53 locations, 92 exits, 31 npcs, 83 items, 14 shops
  sewers/        — 40 locations, 79 exits, 15 monsters, 73 spawns
schemas/         — JSON Schema validation for all entity types
VERSION          — content version (must match engine compatibility)
```

## Usage

Clone next to the engine repo:
```bash
git clone https://github.com/AriesT/realm-of-echoes-world ../realm-of-echoes-world
```

Then in the engine `.env`:
```
WORLD_PATH=../realm-of-echoes-world
```

## Validate

```bash
./roe world-validate
```

## Compatibility

| World | Engine |
|-------|--------|
| 1.0   | >=1.0  |

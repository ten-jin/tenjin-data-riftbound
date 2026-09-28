# tenjin-data-riftbound

Declarative data structures for playing Riftbound with the Tenjin TCG engine.

## Files

`Riftbound.json` defines the game rules, available `cards` + their effect definitions for playing with, and a default unrestricted game mode.

Modes define match length, player count, scoring, deck construction, draws, mulligans, and any rule overrides.

The unrestricted mode overrides `sets` and `banned` so you can play with any available card.

## Usage in Tenjin

1. Download `Riftbound.json` and any additional modes you wish to play with
2. Visit [tenjin.cards](https://tenjin.cards) and drop `Riftbound.json` into the game config panel
3. Import decks from your favorite [source](https://piltoverarchive.com/decks) (several common formats are accepted)

## Versioning

Game updates use `MAJOR.MINOR.PATCH`:
- Major: new set release
- Minor: new cards or functionality, data structure change or engine update required
- Patch: bug fix compatible the existing engine and data contract

## Data format documentation

See [github.com/ten-jin/tenjin-schema](https://github.com/ten-jin/tenjin-schema) for more detail.

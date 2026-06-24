# APlankMaker

APlankMaker is a DreamBot plank-production script by A167881.

![APlankMaker](assets/aplankmaker-v3-200.png)

## Modes

- **Simple:** uses owned supplies, selects the highest supported log tier, and chooses an accessible sawmill route automatically.
- **Advanced:** provides manual log, sawmill, transport, equipment, restock, selling, and runtime controls.
- **Lunar Plank Make [BETA]:** runs a separate Lunar spell workflow with rune, staff, rune-pouch, bank-position, optional restock, and optional safe-world hopping controls.

## Installation

1. Download `releases/AI-Plank-Maker-DreamBot-Public.jar`.
2. Place it in the DreamBot `Scripts` directory.
3. Refresh DreamBot Local Scripts.
4. Start `APlankMaker`.

The jar targets Java 8 bytecode for DreamBot compatibility.

## Release Status

- **Current public release:** v3.9
- Simple and Advanced sawmill workflows are the primary production modes.
- GE restocking and selling are marked BETA.
- Woodcutting Guild and Prifddinas routing are marked BETA.
- Lunar altar switching, Lunar Plank Make, and Lunar world hopping are marked BETA.
- Ironman mode disables all Grand Exchange actions.
- BETA capabilities are available for users who want to help evaluate newer workflows. For the most predictable experience, use the primary Simple or Advanced sawmill modes and leave BETA options disabled.

## Source And SDN

This public repository intentionally ships the release jar, SDN submission notes, icon asset, and checksum only. The proprietary source is not distributed here.

DreamBot SDN submission uses the repository/module fields provided in the DreamBot scripter panel. Use the prepared private source module from the local build output for that SDN repository.

## Verification

See `SHA256SUMS.txt` for the release checksum.

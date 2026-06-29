# APlankMaker

APlankMaker is a DreamBot plank-production script by A167881.

![APlankMaker](assets/aplankmaker-v3-200.png)

## Modes

- **Simple:** uses owned supplies, selects the highest supported log tier, and chooses an accessible sawmill route automatically.
- **Advanced:** provides manual log, sawmill, transport, equipment, restock, selling, and runtime controls.
- **Lunar Plank Make [BETA/experimental]:** runs a separate Lunar spell workflow with rune, staff, rune-pouch, bank-position, optional restock, altar switching, and optional safe-world hopping controls.

## Public Release

- **Current public release:** v4.33
- **Jar:** `releases/AI-Plank-Maker-DreamBot-Public.jar`
- **DreamBot script/module name:** `APlankMaker`
- **Java compatibility:** Java 8 bytecode; source validated with `javac --release 8` for SDN compatibility.
- **QuickStart:** No
- **Ironman supported:** Yes. Ironman mode disables Grand Exchange restocking and selling.

## Features

- Simple and Advanced sawmill workflows are the primary production modes.
- Auburnvale, Prifddinas, Woodcutting Guild, and Varrock sawmill routing are supported and are not BETA.
- Owned-supply processing, runtime editing, breaks, live statistics, and diagnostic logging are included.
- Public Report button sends sanitized runtime summary, APlankMaker diagnostic log, newest DreamBot log when available, and a best-effort DreamBot canvas screenshot when available.
- GE restocking and selling are optional BETA features.
- Lunar Plank Make, Lunar altar switching, and Lunar world hopping are optional BETA/experimental features.

## Installation For Local Testing

1. Download `releases/AI-Plank-Maker-DreamBot-Public.jar`.
2. Place it in the DreamBot `Scripts` directory.
3. Refresh DreamBot Local Scripts.
4. Start `APlankMaker`.

## Source And SDN

This public repository intentionally ships the compiled release jar, SDN submission notes, icon asset, notice, and checksum only. The proprietary source is not distributed here.

DreamBot SDN submission uses the repository/module fields provided in the DreamBot Scripter Panel. Use the private DreamBot-hosted source repository/module for SDN compile, not this public GitHub repository.

## Verification

See `SHA256SUMS.txt` for the release checksum.

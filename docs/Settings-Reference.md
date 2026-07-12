![Script](https://img.shields.io/badge/Script-APlankMaker-00bcd4) ![Public](https://img.shields.io/badge/Public-Guide-2a9d8f)

[Wiki Hub](Home) | [APlankMaker](APlankMaker) | [Report Bugs](Overlay-And-Bug-Reports)

# Settings Reference

## Mode

Simple Mode automatically chooses owned supplies and an accessible sawmill route.

Advanced Mode lets you choose logs, sawmill, transport, gear, and runtime options.

Lunar Plank Make is a spell-based mode and requires the account to start on the Lunar spellbook.

See [Requirements And Unlocks](Requirements-And-Unlocks) before using route-specific or spell-based options.

## Plank Target

The number of planks to make before stopping. `0` means unlimited.

## Gear Preference

Controls equipment setup for Simple and Advanced modes. Auto/Graceful-style movement gear is the recommended default.

Lunar-specific outfit presets are not shown here. Lunar Plank Make has its own optional equipment-slot selector for cosmetic or utility choices.

## Ironman Mode

Disables Grand Exchange actions, including restocking and selling.

## Experimental Restock / GE Planning

Allows normal accounts to use Grand Exchange restocking logic. Leave this off for owned-supply runs.

## Breaks

Allows longer scheduled rest windows in addition to smaller idle behavior.

Breaks and idle behavior are part of the public humanized runtime behavior. See [Humanized Runtime Behavior](Humanized-Runtime-Behavior).

## Lunar Target Logs

Controls which logs Lunar Plank Make should process. Auto chooses the highest supported available option.

## Lunar Casting

AFK casts once and allows the automatic inventory sequence to continue. Active recasts each log for higher throughput. Random varies between both styles by inventory. AFK is the default.

## Lunar World Hopping

Optional world changes on a saved timed range while avoiding unsafe or unsuitable worlds.

The overlay shows the live hop countdown after startup and after saved runtime edits.

If the account is already in a usable members world, the script should not need to hop before starting.

## Lunar Bank Spot Rotation

Optional rotation between validated casting tiles beside the current supported bank on a saved timed range.

The overlay shows the live bank-spot countdown beside the world-hop countdown.

## GE Selling

Experimental option for selling planks after restock cycles on normal accounts. Disabled by Ironman mode.





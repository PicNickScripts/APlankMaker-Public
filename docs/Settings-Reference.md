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

Allows normal accounts to test Grand Exchange restocking in Advanced or Lunar mode. Advanced buys the missing difference up to the target while retaining processing coins. Simple Mode does not show or run GE actions.

## Breaks

Allows longer scheduled rest windows in addition to smaller idle behavior.

Breaks and idle behavior are part of the public humanized runtime behavior. See [Humanized Runtime Behavior](Humanized-Runtime-Behavior).

## Lunar Target Logs

Controls which logs Lunar Plank Make should process. Auto chooses the highest supported available option.

## Lunar Casting

AFK casts once and allows the automatic inventory sequence to continue. Active recasts each log for higher throughput. Random varies between both styles by inventory. AFK is the default.

## Lunar World Hopping

Optional world changes on a saved 1-240 minute range while avoiding unsafe or unsuitable worlds. The next hop is selected within the entered minimum and maximum.

The overlay shows the live hop countdown after startup and after saved runtime edits.

If the account is already in a usable members world, the script should not need to hop before starting.

## Lunar Bank Spot Rotation

Optional rotation between validated casting tiles beside the current supported bank on a saved 1-240 minute range. The next rotation is selected within the entered minimum and maximum.

The overlay shows the live bank-spot countdown beside the world-hop countdown.

## GE Selling

Experimental option for selling planks after restock cycles in Advanced and Lunar modes. Hidden in Simple Mode and disabled by Ironman mode.





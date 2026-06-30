# DreamBot SDN Submission

1. **Category:** Moneymaking
2. **Name:** APlankMaker
3. **Description:** Makes planks at supported sawmills with Simple auto-routing and Advanced controls for Auburnvale, Prifddinas, Woodcutting Guild, and Varrock. Supports owned-supply processing, Ironman-safe behavior, humanized mouse and idle behavior, breaks, and optional equipment setup. Optional experimental workflows include GE restocking/selling and Lunar Plank Make.
4. **Search tags:** plank maker, sawmill, construction, mahogany plank, teak plank, oak plank, lunar plank make, auburnvale
5. **Thread URL:** Create the script thread in the DreamBot SDN Scripts forum, then paste its full URL.
6. **Image:** `assets/aplankmaker-v3-200.png`
7. **Ironman Supported:** Yes
8. **QuickStart Supported:** No
9. **VIP Features Required:** No
10. **Script Type:** Free
11. **Script Repo:** `adreareehx`
12. **Script Module:** APlankMaker
13. **SDN Parameters:** Leave blank
14. **Request Notes:** Java 8-compatible source that also compiles under DreamBot's Java 11 SDN compiler. Simple and Advanced sawmill flows are the stable primary modes. Supported sawmill routes include Auburnvale, Prifddinas, Woodcutting Guild, and Varrock. Runtime includes humanized mouse/idle behavior and breaks without requiring QuickStart parameters. GE restocking/selling, Lunar altar switching, Lunar Plank Make, and Lunar world hopping are experimental. Ironman mode disables all GE actions. QuickStart is not supported; SDN Parameters should be left blank.

## Required SDN Module

The private source module is maintained separately and is intentionally not included in this public release repository. Copy the `APlankMaker` module into the root of the DreamBot-hosted repository. The required layout is:

```text
DreamBotRepository/
+-- APlankMaker/
    +-- src/
        +-- com/
            +-- plankmaker/
                +-- ...
```

The DreamBot form does not accept a jar upload. DreamBot compiles the Java source from its own hosted repository.

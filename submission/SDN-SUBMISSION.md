# DreamBot SDN Submission

1. **Category:** Moneymaking
2. **Name:** APlankMaker
3. **Description:** Makes planks at supported sawmills with Simple auto-routing and Advanced controls for Auburnvale, Prifddinas, Woodcutting Guild, and Varrock. Includes Lunar Plank Make with AFK, Active, and Random casting. Supports owned supplies, Ironman-safe behavior, breaks, and optional equipment setup. Advanced and Lunar GE restocking and selling are experimental.
4. **Search tags:** plank maker, sawmill, construction, mahogany plank, teak plank, oak plank, lunar plank make, auburnvale
5. **Thread URL:** Create the script thread in the DreamBot SDN Scripts forum, then paste its full URL.
6. **Image:** `assets/aplankmaker-v3-200.png`
7. **Ironman Supported:** Yes
8. **QuickStart Supported:** No
9. **VIP Features Required:** No
10. **Script Type:** Free
11. **Script Repo:** `adreareehx`
12. **Script Module:** PicNickScripts
13. **SDN Parameters:** APlankMaker
14. **Request Notes:** Java 8-compatible source that also compiles under DreamBot's Java 11 SDN compiler. Supported sawmill routes include Auburnvale, Prifddinas, Woodcutting Guild, and Varrock. Lunar Plank Make requires the account to start on the Lunar spellbook. GE restocking and selling are experimental in Advanced and Lunar modes. Simple Mode uses owned supplies only, and Ironman mode disables all GE actions. QuickStart is not supported; SDN Parameters should be set to APlankMaker.

## Required SDN Module

The private source module is maintained separately and is intentionally not included in this public release repository. Copy the `PicNickScripts` module into the root of the DreamBot-hosted repository. The required layout is:

```text
DreamBotRepository/
+-- PicNickScripts/
    +-- src/
        +-- MainEntryPoint.java
        +-- com/
            +-- plankmaker/
                +-- ...
```

The DreamBot form does not accept a jar upload. DreamBot compiles the Java source from its own hosted repository.



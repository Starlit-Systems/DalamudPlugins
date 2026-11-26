# Starlit Systems Dalamud plugins

FINAL FANTASY XIV plugins by Starlit Systems, installable through Dalamud.

## Installing

1. In game, type `/xlsettings` and open the **Experimental** tab.
2. Under **Custom Plugin Repositories**, paste this address, press the **+** button, then **Save and Close**:

   ```text
   https://raw.githubusercontent.com/starlit-systems/DalamudPlugins/main/pluginmaster.json
   ```

3. Type `/xlplugins`, search for the plugin by name and install it.

## Plugins

| Plugin | What it does | Source |
|---|---|---|
| **SubLedger** | An accounting ledger for your Free Company submarines: records what every voyage earns at NPC vendor prices, with reports, charts and exports. Open with `/subledger`. | [starlit-systems/SubLedger](https://github.com/starlit-systems/SubLedger) |
| **Honorific Carousel** | Rotates your saved Honorific titles on a per-character timer. Needs Honorific. | [starlit-systems/HonorificCarousel](https://github.com/starlit-systems/HonorificCarousel) |

## For maintainers

`pluginmaster.json` is the list Dalamud reads. Each plugin's own repository builds and publishes its release; after a release, set that plugin's `AssemblyVersion` here to the new version and push.

The older address, `https://raw.githubusercontent.com/starlit-systems/HonorificCarousel/main/pluginmaster.json`, is kept in step with this one so people who added it earlier still receive updates.

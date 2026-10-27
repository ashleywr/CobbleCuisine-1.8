# 🍱 CobbleCuisine

*A Cobblemon side-mod for Fabric (1.21.1) that adds flavorful food mechanics for trainers and their Pokémon — made with love, spice, and a sprinkle of chaos!*

---

## 🌟 What is CobbleCuisine?

**CobbleCuisine** is a feature-rich cooking side-mod for **Cobblemon** that lets you cook meaningful meals or feed your Pokémon stylish snacks.

This mod brings flavorful mechanics to the table while blending with vanilla and modded worlds seamlessly.

---

## 🍔 Features

- **🫘 Beans**  
  Collect, grow and feed **coloured beans** to your Pokémon to **boost friendship** in a cute and customizable way!


- **🥪 Sandwiches**  
  Crafted to **attract Pokémon of specific Tera Types** during spawn cycles!  
  Sandwiches come in various flavours tied to a Tera Type boost!


- **🍛 Curries**  
  Each curry dish attracts Pokémon of a **specific Pokémon type**! Delicious, cozy, and type-aligned!


- **🥗 Salads**  
  Trigger status effects that **influence Pokémon natures** during spawn.  
  Want a *Jolly* or *Bold* Pokémon? There’s a salad for that!


- **🍰 Cakes**  
  Feed these sugary delights to **influence egg group-based spawns**, perfect for breeders!


- **🥤 Shakes**  
  A new line of EV-training items! Boost your Pokémon’s stats with nutritious and sparkly shakes!


- **🎯 Special Effect Foods**  
  Some foods apply general bonuses like:
    - Increased shiny rate
    - Better catch rates
    - EXP multipliers
    - IV and size boosts
    - And more!


- **🌐 Full language support**  
  Translations included: **English**, **日本語**, **繁體中文**

---

## 🧩 Compatibility and Requirements

- ✔️ Minecraft `1.21.1`
- ✔️ Fabric API
- ✔️ Cobblemon `1.6.1`
- ❓ Support for other mods coming soon!

---

## 💖 Credits
Fyre520, tredevelops, EasyMochi

Special thanks to:
- The **Cobblemon** team

---

## ⚠️ Disclaimer

This mod is a **fan-made project** and is **not affiliated with or endorsed by Nintendo, Game Freak, or The Pokémon Company**.  
All Pokémon-related content, including names, types, and trademarks, are the property of their respective owners.

**CobbleCuisine** was made with love for the community and aims to enrich the fan experience while respecting the original IP.

If you are the owner of any referenced content and wish for changes or removal, please feel free to contact us!

---

*Now go cook something magical, trainer!* 🍳✨

<!-- ashley-release-information -->

## My builds

This is an unofficial maintenance fork. Original authors retain ownership and credit. See the [upstream project](https://github.com/Fyre520/CobbleCuisine-Java) for the original mod. Local changes do not imply upstream endorsement.

Licensing: **MIT**. Existing license files, copyright notices, attribution and any separate asset terms remain in force. This fork does not relicense upstream work.

Provided **AS IS**, without warranty of any kind. Maintenance, updates and support are best effort; compatibility with every modpack is not guaranteed.

### Downloads and installation

Download a runtime `.jar` from [GitHub Releases](https://github.com/ashleywr/CobbleCuisine-1.8/releases). Use the Minecraft version and loader named in that release and install its required dependencies. Do not install `-sources`, `-dev`, `-slim`, `-common` or test JARs as the mod.

Close Minecraft, back up your world, and place the matching runtime JAR in the instance's `mods/` directory. Replace older versions of this same mod rather than loading duplicates. For content mods, install matching versions on the server and its clients unless the release explicitly says client-only or server-only.

### Building and reporting problems

Use Java 21 and the checked-in Gradle wrapper:

```powershell
.\gradlew.bat build
```

Build outputs are under `build/libs/` or each loader subproject's `build/libs/`. Some projects require the local development dependencies described above; those dependencies are not included in the download.

For a problem report, include the exact release filename, Minecraft and loader versions, relevant mod versions, `logs/latest.log`, and a crash report if one was written. Remove private information before sharing logs. Remove the JAR to uninstall; worlds containing this mod's blocks, entities or world generation may require restoring a backup.

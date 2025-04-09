### Honesty: Created World | v1.3

_Minecraft 1.20.1_ | _Forge 47.3.0_ 


### Changes/Improvements ⭐

- **Better Combat:** Has better integration with Tinkers Construct.
- **New Weapons:** Tinkers Construct has a few new weapons available.
- **Performance:** Addressed some problematic mods causing performance or loading time issues.
- **Map Expansion:** The map expansion is complete. Please keep long term builds within 7k of spawn for future world trimmings if possible.


### Bug Fixes 🐛

- **Washing Crushed Lead:** This is now possible, resulting in 9 lead nuggets.
- **Third Person:** Is now reverted to vanilla. This resolves third person issues on moving vehicles.
- **Updates:** Updated the following mods: `supplementaries`, `moonlight`, `tinkersconstruct`, `mantle`.


### Added Mods ✅

- [Tinker and Better Combat](https://www.curseforge.com/minecraft/mc-mods/tinker-and-better-combat)
- [Tinkers' JSON Things](https://www.curseforge.com/minecraft/mc-mods/tinkers-things-json)
- [Create: Less Ticking](https://www.curseforge.com/minecraft/mc-mods/create-less-ticking)


### Removed Mods ❌

- [Recipe Essentials](https://www.curseforge.com/minecraft/mc-mods/recipe-essentials-forge-fabric)
- [Better Third Person](https://www.curseforge.com/minecraft/mc-mods/better-third-person)
- [Lets Do Beach Party](https://www.curseforge.com/minecraft/mc-mods/lets-do-beachparty)


---------------------------------------------------------------------------------------------------------------------------------------------------------------

### Honesty: Created World | v1.2

_Minecraft 1.20.1_ | _Forge 47.3.0_ 


### Changes/Improvements ⭐

- **Main Menu:** Remixed the Legacy RST Create menu for the Honesty series. Volume is controlled by the Jukebox/Noteblock audio options.
- **Better Combat:** We are giving the Better Combat system a shot. It has compatibility with Alexs Caves.
- **Removed Bloat:** Removed some redundant mods to improve load times and reduce the number of items.
- **Shader Optimizations:** Several updates to shaders and their integration with Create to enhance performance. (There are issues with Complementary)
- **Resource Packs:** Added/removed textures and animations to achieve a dark mode + Create themes.
- **Quests:** Added several new quests as well as a money themed quest meant for mid to late or even post game content. (WIP)
- **Server Config Tweaks:** Some things have been tweaked server-side that can't be reflected on SSP.
- **Dynmap:** Will be up and ready to go sometime this patch.


### Bug Fixes 🐛

- **Sheet Recipes:** There were conflicts in how sheets were handled in recipes. I applied a script to fix this by allowing any plate of the correct material for recipes.
- **Super Heated Blaze Burners:** Previously, giving the burners a Blaze Cake only heated them. Now, they should superheat as intended, and you should see them turn blue.
- **AE2 Polymorph:** It was impossible to polymorph craft items that had the same recipe as others in AE2 interfaces. There is now a Polymorph button within ME Terminals.
- **Unique Item Stacks:** It was possible to offhand a Create item, and its NBT data would become corrupted, causing it not to stack with other identical items.
- **Invisible Enemies:** It was possible to encounter a fully invisible monster in the world. This should be fixed now.
    - If they ever appear invisible to you, ensure that both `Block Face Culling` and `Max Block Entity` are disabled in Video options.
- **Item Tags:** Using some scripts, I made some item tags to make searching easier:
    - Searching `$agriculture`, `$decor_stations`, or `$doughs` in JEI will narrow down to a group of `@mod` or `@item` tags I felt would fit in this category.
    - If you can think of more useful tags, let me know!
- **Food Plates:** There were compatibility issues with crafting food display plates. You should be able to craft them now, and their recipes should show in JEI.
- **Chisel/Chipped Compatibility:** There should be more cross-compatibility between Chisel and Chipped in general.
- **Wood Support:** I can't fix them all, but more of the custom woods should at least be usable to make chests now.
- **Quest Book:** Ensured you receive a quest book on first login now.
- **Removed Craft:** Made Suspicious Sand and Suspicious Gravel uncraftable.
- **AE2 Cables:** You can now 2x2 craft the normal cables to get their dense version.
    - Again, let me know of other recipes like this we could add or change!
- **Trackwork:** Wheels and components would show as invisible. This should be corrected now.
    - If they ever appear invisible to you, ensure that both `Block Face Culling` and `Max Block Entity` are disabled in Video options.
- **Broken Quests:** Removed broken quests or fixed existing ones.


### Known Issues ☹️

- **Complementary Shaders + Essential:** There is an issue with the Essential suite and Complementary Shaders specifically that causes enchanted glint items to appear as solid black in inventory screens randomly.
    - You can work around this by removing Essential, which is a cosmetic MTX add-on.
    - Alternatively, you can use a different shader, such as the included MakeUp - Ultra Fast, or any other shader you prefer.
    - Lastly, you can just deal with it I guess!
- **Complementary Shaders:** There is an issue when toggling Complementary Shaders off and back on; the game will crash. The game runs fine with the shaders, but switching back and forth is not possible.
    - You can toggle shaders back on without crashing by switching to MakeUp - Ultra Fast, enabling shaders, and then switching back to Complementary Shaders.


### Added Mods ✅

- [Fancy Menu](https://www.curseforge.com/minecraft/mc-mods/fancymenu)
- [Drippy Loading Screen](https://www.curseforge.com/minecraft/mc-mods/drippy-loading-screen)
- [Better Combat](https://www.curseforge.com/minecraft/mc-mods/better-combat-by-daedelus) (+ Compatibilities)
- [Alexs Caves](https://www.curseforge.com/minecraft/mc-mods/alexs-caves)
- [Better 3rd Person](https://www.curseforge.com/minecraft/mc-mods/better-third-person)
- [LMFT](https://www.curseforge.com/minecraft/mc-mods/lmft)
- [Polymorphic Energistics](https://www.curseforge.com/minecraft/mc-mods/polymorphic-energistics)
- [KubeJS Create](https://www.curseforge.com/minecraft/mc-mods/kubejs-create)
- [Oculus](https://www.curseforge.com/minecraft/mc-mods/oculus) (Downgraded from 1.8.0 to 1.7.0)
- [Iris & Oculus Flywheel Compatibility](https://www.curseforge.com/minecraft/mc-mods/iris-flywheel-compat)
- [AllTheLeaks](https://www.curseforge.com/minecraft/mc-mods/alltheleaks)
- [Create Sabers](https://www.curseforge.com/minecraft/mc-mods/create-sabers)
- [CreateStuffAdditions Fix](https://www.curseforge.com/minecraft/mc-mods/createstuffadditions-fix)
- [Trash Cans](https://www.curseforge.com/minecraft/mc-mods/trash-cans)
- [Chipped Express](https://www.curseforge.com/minecraft/mc-mods/chipped-express)
- [Rechiseled: Chipped](https://www.curseforge.com/minecraft/mc-mods/rechiseled-chipped)
- [Moogs Voyager Structures](https://www.curseforge.com/minecraft/mc-mods/moogs-voyager-structures)
- [Enchantment Descriptions](https://www.curseforge.com/minecraft/mc-mods/enchantment-descriptions)
- Performance related mods and dependencies


### Removed Mods ❌

- [Iron Chests](https://www.curseforge.com/minecraft/mc-mods/iron-chests)
- [Iron Shulker Boxes](https://www.curseforge.com/minecraft/mc-mods/iron-shulker-boxes)
- [ClientTweaks](https://www.curseforge.com/minecraft/mc-mods/client-tweaks)
- [Valkyrien Pirates](https://www.curseforge.com/minecraft/mc-mods/valkyrien-pirates) (+ Dependencies)
- [Create: Better Villager](https://www.curseforge.com/minecraft/mc-mods/create-better-villager)
- [Create: Dynamic Village](https://www.curseforge.com/minecraft/mc-mods/dynamic-village) (Was spamming only one village type.)
- [Lets Do WilderNature](https://www.curseforge.com/minecraft/mc-mods/lets-do-wildernature)
- Some server only mods or dependencies


---------------------------------------------------------------------------------------------------------------------------------------------------------------

## Honesty: Created World | v1.1

_Minecraft 1.20.1_ | _Forge 47.3.0_ 


### Changes/Improvements ⭐

- **QoL:** Various quality of life or streamlined setup updates.
- **Worldborder:** Worldborder will be increased slightly to allow new resources to generate. (Air War Mod)
- **Storage Update:** Transitioning to [Sophisticated Storage](https://www.curseforge.com/minecraft/mc-mods/sophisticated-storage).
- **Resource Packs and Shaders:** Updated; these are optional and can be adjusted client-side. Check the resource pack options or shader pack options. See Discord channel for advice or opinions.
- **MobGrief:** Currently enabled, but things that explode shouldn't do world damage. Please report anything that causes world damage.
- **Dynmap:** Currently a work in progress; updates will be provided.


### Teleports 🪄

Some new restrictions are in place.

- `/home` Now has a 5 second warm up, and a 10 minute cooldown. Look for other ways around this if it annoys you! (In game items)
- `/tpa NAME` Also has a 5 second warmup, and a 5 minute cooldown.
- `/spawn` Has a 5 second warmup.
- `/rtp` Has  been disabled.
- `/back` Can now be used once every hour after a death *only*.
- Removed cheaty commands from access.



### Keybinds & Options 🎮

Some default options have changed or been removed to help streamline getting started.

- **Airship Descend:** Changed from default `V` to `LEFT CTRL`.
- **Carry:** Changed from default holding `SHIFT` + `RIGHT CLICK` to `~` + `RIGHT CLICK`.
- **Zoom:** Changed from default `C` to `Z`. Prevents conflict with `Cruise Control` and is traditional.
- **Sort:** Default key set to `MIDDLE CLICK`.
- **Minimap:** Normalized default position to top right corner.
- **Performance:** Defaulted some options aiming for best performance or avoiding visual issues with VS x Create.
- **Backpack:** Ensured `B` is the only key that uses this.
- **Q:** Rebound to open wireless terminal, if available. This prevents accidental item drops. Rebind if you dislike this.
- **R:** Has been unbound from `Reload Shaders`.
- **Disable Shaders:** Has been rebound to `LEFT CTRL` + `R`.
- **Left Alt:** Is dedicated to `Create Radial Wheels`.
- **Add Waypoint:** Is now bound to `J`.
- **Chat:** Is now bound to `ENTER`.


### Added Mods ✅

- [Macaw's Windows](https://www.curseforge.com/minecraft/mc-mods/macaws-windows)
- [Macaw's Trapdoors](https://www.curseforge.com/minecraft/mc-mods/macaws-trapdoors)
- [Macaw's Roofs](https://www.curseforge.com/minecraft/mc-mods/macaws-roofs)
- [Macaw's Lights and Lamps](https://www.curseforge.com/minecraft/mc-mods/macaws-lights-and-lamps)
- [Macaw's Paths and Pavings](https://www.curseforge.com/minecraft/mc-mods/macaws-paths-and-pavings)
- [Macaw's Stairs](https://www.curseforge.com/minecraft/mc-mods/macaws-stairs)
- [Macaw's Biomes O' Plenty](https://www.curseforge.com/minecraft/mc-mods/macaws-biomes-o-plenty)
- [Macaw's Oh The Biomes You'll Go / We've Gone](https://www.curseforge.com/minecraft/mc-mods/macaws-byg-bwg)
- [Create: Better Villager](https://www.curseforge.com/minecraft/mc-mods/create-better-villager)
- [Create: More Sand Papers](https://www.curseforge.com/minecraft/mc-mods/create-more-sand-papers)
- [Create: Tinker's Compat](https://www.curseforge.com/minecraft/mc-mods/create-tinkers-compat)
- [Create: The Air War](https://www.curseforge.com/minecraft/mc-mods/create-the-air-war)
- [Valkyrien Skies: Tournament](https://www.curseforge.com/minecraft/mc-mods/valkyrien-skies-tournament)
- [Valkyrien Pirates](https://www.curseforge.com/minecraft/mc-mods/valkyrien-pirates) (They grief so I disabled their shooting mechanics for now)
- [Sophisticated Storage](https://www.curseforge.com/minecraft/mc-mods/sophisticated-storage)
- [Tinkers Delight](http://curseforge.com/minecraft/mc-mods/tinker-delight)
- [Let's Do WilderNature](https://www.curseforge.com/minecraft/mc-mods/lets-do-wildernature)
- [Let's Do Fluids](https://www.curseforge.com/minecraft/mc-mods/lets-do-addon-fluids)
- [Building Gadgets](https://www.curseforge.com/minecraft/mc-mods/building-gadgets)
- [Gadgets Against Grind](https://www.curseforge.com/minecraft/mc-mods/gag)
- [Akashic Tome](https://www.curseforge.com/minecraft/mc-mods/akashic-tome) (Combine all books)
- [Morph-o-Tool](https://www.curseforge.com/minecraft/mc-mods/morph-o-tool) (Combine all wrenches)
- [Immersive UI](https://www.curseforge.com/minecraft/mc-mods/immersive-ui)
- [What are they upto?](https://www.curseforge.com/minecraft/mc-mods/what-are-they-up-to)
- [Chat Heads](https://www.curseforge.com/minecraft/mc-mods/chat-heads)
- [Client Tweaks](https://www.curseforge.com/minecraft/mc-mods/client-tweaks)
- [Better Compatibility Checker](https://www.curseforge.com/minecraft/mc-mods/better-compatibility-checker)
- [Perception](https://www.curseforge.com/minecraft/mc-mods/perception)
- [Euphoria Shaders Addon](https://www.curseforge.com/minecraft/mc-mods/euphoria-patches) (Extends shaders even further)
- Dependencies


### Removed Mods ❌

- [Create: Gourmet](https://www.curseforge.com/minecraft/mc-mods/create-gourmet)
- [Create: Cafe](https://www.curseforge.com/minecraft/mc-mods/create-cafe)
- [Create: Factory](https://www.curseforge.com/minecraft/mc-mods/create-factory)
- [Create: Confectionery](https://www.curseforge.com/minecraft/mc-mods/create-confectionery)
- [Create: Goggles](https://www.curseforge.com/minecraft/mc-mods/create-goggles)
- [Create: Deepfried](https://www.curseforge.com/minecraft/mc-mods/create-deepfried)
- [Croptopia](https://www.curseforge.com/minecraft/mc-mods/croptopia)
- [Croptopia Delight](https://www.curseforge.com/minecraft/mc-mods/croptopia-delight)
- [Mighty Mail](https://www.curseforge.com/minecraft/mc-mods/mighty-mail) (Replaced by MrCrayFish Furniture)
- [Straw Statues](https://www.curseforge.com/minecraft/mc-mods/straw-statues)
- [Domum Ornamentum](https://www.curseforge.com/minecraft/mc-mods/domum-ornamentum)
- [Builders Delight](https://www.curseforge.com/minecraft/mc-mods/builders-delight)
- [Bad Mobs](https://www.curseforge.com/minecraft/mc-mods/bad-mobs)
- [Via Romana](https://www.curseforge.com/minecraft/mc-mods/via-romana)
- [Butchers Delight](https://www.curseforge.com/minecraft/mc-mods/butchers-delight)
- [Oceans Delight](https://www.curseforge.com/minecraft/mc-mods/oceans-delight)
- [Aether Delight](https://www.curseforge.com/minecraft/mc-mods/aether-delight)

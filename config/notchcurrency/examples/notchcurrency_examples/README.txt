Notch Currency example datapack
-------------------------------
This folder is a ready-to-use datapack with the mod's default bounties,
loot crates and cosmetics shop offers. It does nothing where it is.

To use it:
  1. Copy this whole folder into your world's datapacks folder, so it ends
     up at <world>/datapacks/notchcurrency_examples/
     On a server, the world folder is usually called "world".
  2. Edit the JSON files inside data/.
  3. Run /reload in game, or restart.

How the files work:
  - A file with the same path as one of the mod's files replaces it.
    data/notchcurrency/notch_bounties/objectives/default.json replaces
    the default bounty list. Make it [] to turn the defaults off.
  - A file with a new name adds to the mod's list instead.

pack.mcmeta is set up for Minecraft 26.1.2. If you move to another Minecraft
version, copy this folder again.

The mod refills this folder when it starts: a deleted file comes back,
but files you changed are kept. The wiki's Configuration page lists
every field.

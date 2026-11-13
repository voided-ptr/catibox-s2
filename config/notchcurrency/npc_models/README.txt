Custom NPC models for Notch Currency
------------------------------------
One folder per model. The folder name is the model's id, and may only use
lowercase letters, numbers and underscores.

  npc_models/
    town_guard/
      model.geo.json     from Blockbench: File > Export > GeckoLib Animated Model
      animation.json     from Blockbench, if the model is animated
      texture.png
      npc.json           optional, see below

npc.json is optional. Without it the mod uses the folder name and looks for
clips called "idle" and "walk". With it you can be explicit:

  {
    "name": "Town Guard",
    "author": "you",
    "scale": 1.0,
    "hitbox": { "width": 0.6, "height": 1.95 },
    "clips": {
      "idle": "animation.guard.idle",
      "walk": "animation.guard.walk",
      "special": ["animation.guard.wave"]
    }
  }

Drop working files in _import if you like; that folder is ignored.

Common problems the mod will tell you about:
  - Exported as Java Block/Entity instead of GeckoLib Animated Model
  - texture.png is a different size than the model expects
  - npc.json names a clip the animation file does not have

# x4-Better-piracy
_X4 Foundations mod to improve piracy_

## Compatibility
Compatible with `3.x`, with and without `Split vendetta`.

Savegame friendly. (Both adding and removal)

## Description
This mod addresses several piracy gameplay-aspects in X4 that I really dislike.

If you want to force some S/M ship to bail or soften an L/XL ship before boarding, right-click it, choose "Harass" and follow the instructions.

Also, you can configure it as much as you want using the in-game menu.

## Major changes explanation

### Replaced `Surrender!` dialog option by `Harass` contextual action.
Replaced the confusing and mostly random `Surrender!` dialog option by a more streamlined `Harass` contextual menu action.

If you want to force some S/M ship to bail, or soften an L/XL ship before boarding, right-click it and choose `Harass`.

That will start a mission, follow the steps and the prize will be yours.

### Create your own pirate gang.
Subordinates of the ship you are piloting will smartly participate in the "Harass operation", helping you while avoiding killing the target.

Tip: Use ships with a lot of shields and prefer high-shield/low-hull damage weapons for maximum effectiveness.

### Create your own pirate imperium.
You will be able to instruct your most experienced pilots (3 stars or more) to do harass operations on their own, just assemble a small fleet and assing the `Corsair` default order to their leader.

Tip: The _Argon trading station_ in _Hatikvah's Choice I_ is usually full of HOP and ZIA traders (ARG/HAT will not protect nor care about them), that's a good spot to start.

### Added a lot of config options to let you tune the piracy
Added more than 20 configuration options to let you tune the mod to your likings.

## Minor changes explanation

### Removed "Ship type penalty" from the bailing calculation
Before, you were heavily punished if you were flying a ship with a higher `maxHull` than the enemy you were harassing.

This has been removed.

### Improved feedback when crew bails
If the crew is bailing out of the ship, a notification will appear of the lower-left corner detailing it.

### Piracy is a crime!
By default, nobody cared about piracy, you could hijack 1000 ships in front of them and you will still be their best friend.

Now, piracy is a crime, and if you do it enough, people will consider you a criminal.

### Removed boarding pods orbiting ship when using marines to claim a ship
When using marines to claim a ship, they will use the "Travel drive" to get closer and they will no longer endlessly orbit it.

### Removed extra damage done when claiming with marines
Your marines have been instructed to be as careful as you are when claiming ships, so they will no longer cause any extra damage to the ships they claim.

### Stations will not allow a fleeing ship to dock if the attacker is allied to them
Your allies will no longer protect your enemies from you!

## Credits
 - vx -> Author of `True Capture`, where a lot of inspiration was drawn.
 - Kevrlet -> Author of `FixBailChance`, where a lot of inspiration was drawn.
 - SirNukes -> Author of `SirNukes Mod Support APIs`.
 - Smashicons -> Author of the image used as Thumbnail (https://www.flaticon.es/autores/smashicons)
 - https://text2voice.org, https://twistedwave.com/online, and https://voicechanger.io/ -> All of them used to create the custom dialog lines.

## Changelog
### 0.12.0
 - Updated to use the latest `SirNukes Mod Support APIs` features.
 - Updated German texts. (Thank you @LeLeon)
 - Ships that participate in a successful harass operation will gain experience.
### 0.11.0
 - Created new default order `Corsair`, ships/fleets with this behavior will smartly harass selected enemy targets.
 - Improved Harass operation logic.
 - Improved debug logging.
 - Disabled `combat_reputation_hit` and `harass_reputation_hit`, I need to find a better way of handling it.
 - Stations will not allow a fleeing ship to dock if the attacker is allied to them.
 - Separated changes into `Major changes` and `Minor changes` to increase readability.
### 0.10.0
 - Subordinates of the player ship will smartly participate in the "Harass operation".
### 0.9.0
 - Improved logic to avoid having boarding pods orbiting ship when using marines to claim a ship.
### 0.8.0
 - When using marines to claim a ship, the boarding pod will use the travel drive.
 - Improved logic to avoid having boarding pods orbiting ship when using marines to claim a ship.
### 0.7.0
 - Removed boarding pods orbiting ship when using marines to claim a ship.
 - Added German translation.
 - Added French translation.
### 0.6.0
 - Added custom dialog lines during harass operation, now you know that you are threatening them.
 - Minor fixes.
### 0.5.0
 - Improved the `Harass` command vs capital ships, now it will only soften them.
 - Added distance checks to the `Harass` command, now you really need to stick on the target.
 - Added a lot of config options.
### 0.4.0
 - Reworked all the `RightClick -> Harass` code, not should work much better.
 - Externalized hard-coded texts to I18N files (English and Spanish).
### 0.3.0
 - Removed `Surrender!` dialog, replaced it by a more streamlined `RightClick -> Harass`.
 - Added dependency to "SirNukes Mod Support APIs".
### 0.2.0
 - Forcing a pilot to bail out of their ship will negatively impact your relations with his/her faction.
### 0.1.0
 - Replaced NPCs saying the "Abandon ship!" when they bail by a more discrete, less annoying and more informative notification on the lower-right corner.
 - Expanded `hull%` calculations from `20%` to `75%`, which should make the effects of this mod more gradual.
### 0.0.0
 - Initial release!

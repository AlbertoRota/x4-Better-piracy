# x4-Better-piracy
_X4 Foundations mod to improve piracy_

## Description
This mod addresses several piracy gameplay-aspects in X4 that I really dislike.

Now, if you want to force some S/M ship to bail,, you need to:
 - Keep their shields under 20%.
 - Keep their hull as low as possible, without killing them.
 - Harass them, using any of the following methods:
    - Repeatedly demand them to surrender (As effective as shooting them).
    - Shoot them without killing them (Ion weapons are the best, since they preserve hull).
 - Once they all bail. use a marine to claim the ship, they have been trained to be as careful as you are, so they will not harm the ship any longer.

## Detailed changes explanation

### Removed "Ship type penalty" from the bailing calculation
Before, you were heavily punished if you were flying a ship with a higher `maxHull` than the enemy you were harassing.
This has been removed.

### Number of bailing crew will increase the worse the hull state is
A good pilot (High morale) will be able to keep the crew together, but even the best pilot will have problems doing it if the ship is falling apart under enemy fire.

The worse the hull state is, the less the pilot morale is factored in.

### Bailing check frecuency will increased the worse the hull state is
By default, crew members were only allowed to bail every 30 seconds, but if the ship is falling apart under enemy fire, they will speed up the evacuation process.

Hull degradation will speed this up to every 5s at 1% hull.

### Improved feedback when crew bails
When asking to `Surrender!` or while under enemy fire, is crew is bailing out of the ship, a notification will appear of the lower-right corner detailing it.

### Removed extra damage done when claiming with marines
Your marines have been instructed to be as careful as you are when claiming ships, so they will no longer cause any extra damage to the ships they claim. 

## Credits
 - vx -> Author of `True Capture`, where a lot of inspiration was drawn.
 - Kevrlet -> Author of `FixBailChance`, where a lot of inspiration was drawn.

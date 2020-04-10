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

### Critical hull state will increase the number of bailing crew
A good pilot (High morale) will be able to keep the crew together, but even the best pilot will have problems doing it if the ship is falling apart under enemy fire.

This effect kicks in when the hull reaches 20% and increases the lower the hull percentage is.

### Critical hull state will increase bailing frequency
By default, crew members were only allowed to bail every 30 seconds, but if the ship is falling apart under enemy fire, they will speed up the evacuation process.

This effect kicks in when the hull reaches 20% and increases the lower the hull percentage is up to allowing crew members to bail every 5s at 1% hull.

### Improved feedback when crew bails
When asking to `Surrender!` or while under enemy fire, is crew is bailing out of the ship, they will speak the `Abandon ship!` line.

### Removed extra damage done when claiming with marines
Your marines have been instructed to be as careful as you are when claiming ships, so they will no longer cause any extra damage to the ships they claim. 

## Credits
 - vx -> Author of `True Capture`, where a lot of inspiration was drawn.
 - Kevrlet -> Author of `FixBailChance`, where a lot of inspiration was drawn.

# Preface
 Looting is a pretty safe thing to do, save for the whole 'could be shot at' bit, isn't it? Well, it *was* safe, until now. Watch out for the pointy bits and foreign glands of your to be scavanged corpses...
# Hazardous Looting
 A mod-mod for the Hideous Destructor expansion 'Ugly as Sin'. This mod will do nothing without Ugly as Sin installed.
# Features
 A baseclass called HDHarmfulBox, which upon spawning will:
 - Collide with a player class, then spawn a payload defined by:
 ```
 - damagemin  (minimum forced damage),
 - damagemax  (maximum forced damage),
 - damagetype (the type that the forced damage is),
 - prize      (item to spawn for the player's troubles. Can be blank ("")),
 - visualaid  (vfx actor to spawn (eg, smoke, flames, etc). Can be any actor...).
 ```
 # Compat
  Supports monsters from the following mods by default:
  - HD Re-Enforcements,
  - Vanilla HD.
  Supports items from the following mods by default:
  - OfSpiritsAndShields.
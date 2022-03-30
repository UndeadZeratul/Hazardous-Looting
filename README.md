# Preface
 Looting is a pretty safe thing to do, save for the whole 'could be shot at' bit, isn't it? Well, it *was* safe, until now. Watch out for the pointy bits and foreign glands of your to be scavanged corpses...
# Hazardous Looting
 A mod-mod for the Hideous Destructor expansion 'Ugly as Sin'. This mod will do nothing without Ugly as Sin installed.
# Features
 A baseclass called HDHarmfulBox, which upon spawning will:
 - Collide with a player class, then spawn a payload defined by:
 ```
 - errorthresh    (health value a risk for injury begins at),
 - errorchance    (chance for your hands to slip onto something harmful (%, out of 100)),
 - damagemin      (minimum forced damage),
 - damagemax      (maximum forced damage),
 - burnmin        (minimum forced immolation),
 - burnmax        (maximum forced immolation),
 - damagetype     (the type that the forced damage is),
 - givetargetbody (whether or not to give the target 'body' (enable for melee-type damage)),
 - prize          (item to spawn for the player's troubles. Can be blank ("")),
 - visualaid      (vfx actor to spawn (eg, smoke, flames, etc). Can be any actor...).
 ```
 # Compat
  Supports monsters from the following mods by default:
  - HD Re-Enforcements,
  - Vanilla HD.
  Supports items from the following mods by default:
  - OfSpiritsAndShields.
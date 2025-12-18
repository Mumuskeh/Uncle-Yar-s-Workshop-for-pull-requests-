-Module:
Boomsticks and Sharpsticks [Mich]

----------------------------------------------------------
-Compatibility:

----------------------------------------------------------
-Explanation:

I've seen plenty of people say "BaS guns don't have any parts. Any mods for it?" But thing is, uh, BaS already assigns parts to its guns! But for whatever reason people end up not seeing them.

One possible situation could be overwriting. BaS has its own copy of the vanilla parts.ltx file with its guns added to it. In case some other mod overwrites it, this DLTX file should help ensure this doesn't happen.

Integration into the vanilla dynamic item spawn, reward, and stash systems.

Integration into:
Grok's Stash Overhaul
Weapon Parts Overhaul (same file as in WPO itself, but updated/touched up a lil bit, for example for correct inheritance of AUG and L85 quirks)

----------------------------------------------------------
-Patches:

DLTX Minimod - Bigger Ammo Boxes, and Cheaper Ammo
Makes those two modules cover the BaS ammo. File renamed to ensure being loaded last.
Original modules not required.

BAS SR-2M Reanimated [Synd1cate] Fire position fix.
by hoasd1
1) Set fire_point of all Veresks to "-0.002, 0, 0.14" as it was clipping through the weapon.
2) Fixed aim position of the "wpn_sr2_m1" and "wpn_sr2_m2" variants as it was away from the crosshair.


----------------------------------------------------------
-Known issues:
-Module:
Modular Miscellaneous Tweaks - Suppressor Changes [Vintar0]

----------------------------------------------------------
-Compatibility:
Original mod not required.

----------------------------------------------------------
-Explanation:
DLTX conversion.

The original mod changes the stats of the basic "wpn_addon_silencer" template that all silencers inherit everything from, and removes changed stats from individual silencers.

Technically, all silencers are covered by the mod as long as it inherits its data from "wpn_addon_silencer", but some silencers add their own stat changes, which would need to be squashed.

So, in addition to vanilla silencers, this conversion now also fully applies to silencers from:
-BaS
-AO3 Late Comers
-Blackgrowl's AShey 'n ShAKky
-Lewd's STG44
-Onerock's MCX Spear

Some silencers don't need to be patched, as they already take all stats directly from "wpn_addon_silencer" without changes:
-half of the BaS silencers
-MrB's 10mm Auto Ecosystem
-Joseph Porta's Vulcan
-Maid's Agram 2000

There may be more I missed.


Quoting the original:

This changes how suppressors/silencers affect your weapon. Generally, they apply positive effects at the cost of increased maintenance. Thus, they are meant to be used by experienced STALKERs who can afford to pay the extra costs associated with them.

Adding a suppressor to your gun now applies the following:

+3% bullet speed
+1% gun accuracy
-18% hipfire recoil
-18% aimed recoil
+5% hipfire accuracy (stationary)
-5% hipfire accuracy (moving)
-15% hipfire accuracy (turning)
25% faster gun degradation (due to increased back-pressure and suppressor needing cleaning)

These are all easily editable in the .ltx file.

----------------------------------------------------------
-Patches:

----------------------------------------------------------
-Known issues:
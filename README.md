# coptweaks
Changes the way cops are spawned

About:

This mod changes how the cops are dispatched. Cops no longer spawn trough dispatch.meta (with exceptions to certain units like Helis,Boats and Swat), instead are handled by the game's population

This means that cops don't know where you are, and will spawn patrolling until they spot you passing by or you are in range of their alert radius

You probably should get a popcycle.dat (mod already contains one by default) that has spawn cops in traffic otherwise you get nothing up until you hit 3 stars

Features:
- Cop spawning is handled entirely by popcycle.dat:
	* Amount of patrols can be tuned in popcycle.dat's PercCopCars and PercCopPed values and maybe number next to VEH_COPCAR
	* FIB/NOOSE take the role as pursuers and NOOSE TRU's as dropoff/assault teams in Annihilators
	* polmav no longer spawns at the countryside areas
	* Detectives have a chance of spawning at police stations
	* Includes Merryweather Friendly Fire fix by default
	* Altrough unused in this mod, i've added all police vehicle and ped variants to POLICE_CAR so when player dials 911 to request a police car, the game will pick more than police3 and sheriff cruiser
		- Army Base will not spawn any POLICE_CAR vehicle sets
	* Increased HiddenEvasionTimes, with 4-5 stars being infinite (wait i don't wanna play with IV style search thing, well now you do or change it idc)
	* Increased Thresholds for raising wanted levels, 1-3 is left to default but 4-5 have been increased so 3 stars is bit longer
	* 4-5 stars can either spawn NOOSE or FIB (only 1 per chase)
	* Random SWAT arsenal
	* Removed ImmediateDetectionRange and OnScreenImmediateDetectionRange (both values are 0.0f, refer to vanilla dispatch.meta for their default values if you dont like this change)
	* Removed Herobrine

Known Issues:
* Cops can despawn if player too far away unlike dispatched ones (I am aware of this, and looking for a fix)
* Cops will only spawn with 1 ped per car. (Some hard-coded bs R* implemented for ambient cops, don't know about a fix atm)
* Foot cops will sometimes flee? (I have no idea what causes this, so far shooting near them causes them to go back into combat?)

Skill Issues:
* I can't lose the cops! (Enable IV-Styled Wanted Radius in CombatTweaks.ini, else i'm diagnosing this as skill issue)

Installation:

Drop wantedtweaks folder inside of "lml" folder (Requires Lenny's Mod Loader)

Prob get Cpast's CombatTweaks too (or place the pre-configured combat tweaks asi in your gta5 installation folder)
https://github.com/cpast/GTA_Combat_Tweaks


Credits:
Cpast for CombatTweaks

x3mgamer for Merryweather FF fix, Police Transporter retexture, FIB peds

Yard1 for NOOSE TRU (CADPAT variant)

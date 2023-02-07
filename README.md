# coptweaks
Changes the way cops are spawned and other minor tweaks

About:

This mod changes how the cops are dispatched. Cops no longer spawn trough dispatch.meta (with exceptions to certain units like Helis,Boats and Swat), instead are handled by the game's population
This means that cops won't spawn infront of you or know where you are, and will spawn patrolling until they spot you or get alerted by your sounds

Features:
- Cop spawning is handled entirely by popcycle.dat, but there exceptions:
	* Sheriffs at 3 stars will still spawn at the countryside, since NOOSE was too OP and countryside doesn't have patrolling cops unless you want to sarcifice next-gen cars for cops back on the beat's popgroups.ymt
	* FIB/NOOSE take the role as pursuers and NOOSE TRU's as dropoff/assault teams in Annihilators
	* polmav no longer spawns at the countryside areas
	* Detectives have a chance of spawning at police stations
	* Includes Merryweather Friendly Fire fix by default
	* Altrough unused in this mod, i've added all police vehicle and ped variants to POLICE_CAR so when player dials 911 to request a police car, the game will pick more than police3 and sheriff cruiser
		- Army Base will not spawn any POLICE_CAR vehicle sets
	* Increased HiddenEvasionTimes, with 4-5 stars being infinite (wait i don't wanna play with IV style search thing, well now you do)
	* Increased Thresholds for raising wanted levels, 1-3 is left to default but 4-5 have been increased so 3 stars is bit longer
	* 4-5 stars can either spawn NOOSE or FIB (only 1 per chase)
	* Removed ImmediateDetectionRange and OnScreenImmediateDetectionRange (both values are 0.0f, so Stealth is possible now even if it makes higher wanted level cops dumb)
	* Removed Herobrine

Known Issues:
* Cops can despawn if player too far away unlike dispatched ones (I am aware of this, and looking for a fix)
* Cops will only spawn with 1 ped per car. (Some hard-coded bs R* implemented for ambient cops, don't know about a fix atm)
* Foot cops will sometimes flee? (I have no idea what causes this)

Skill Issues:
* I can't lose the cops! (Enable IV-Styled Wanted Radius in CombatTweaks.ini, else i'm diagnosing this as skill issue)

Installation:

Drop wantedtweaks folder inside of "lml" folder (Requires Lenny's Mod Loader)

Prob get Cpast's CombatTweaks too (or place the pre-configured combat tweaks asi in your gta5 installation folder)
https://github.com/cpast/GTA_Combat_Tweaks


Credits:
Cpast for CombatTweaks
x3mgamer for Merryweather FF fix, Police Transporter retexture, FIB peds

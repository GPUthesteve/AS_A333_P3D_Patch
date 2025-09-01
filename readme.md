# Read Me --English ver.--

# Aerosoft A330 FDE Patch, sound improvements and PFD Rework

# FDE Improvements :
in this section, I give you `"A330-343.air"` airfile and `"aircraft_patch.txt"` source patch config file to be used with your `"aircraft.cfg`
- Fuel Consumption. Simply put, it burns fuel like what it should
- Flight Model and Flight Characteristics, it should behave like every other bus, at least. 

installation :
1. backup your original aircraft.cfg (by copypasta it and name it something else like aircraft_orig.cfg)
2. in `"aircraft.cfg"`, the one which you didnt rename, you're gonna patch it with given `"aircraft_patch.txt"` by
	2.1 replace everything inside `aircraft.cfg` with texts in `aircraft_patch.txt.` now you've patched the config, great.
	2.2 then, you take `[fltsim]` section, aka liveries, back to your `"patched"` config from your backup (to restore your liveries. of course!)
3. now replace your `"A330-343.air"` with given one, back up on your discretion, I suggest don't since old fde flies like shit.

Internal V-speed calculator will broke, please refer to proper A330 Manual or this crude table
![image](https://github.com/user-attachments/assets/1e101b44-cf43-4cf5-81a6-a158e6a4cf71)



# Sound Enhancement
aside FDE patch, I also ship you sound enhancement.
Reworked aural by using A330/A340 RA from the net.

installation
1. navigate to `SimObjects\Airplanes\Aerosoft A330 Professional Base`, you'd see a folder named `sound_asc`, make a backup by simply renaming it to sth else (can skip if don't want to backup, who would?)
2. replace that folder with given `sound_asc` (copy-paste the folder, replace contents if asked, of course). 

# PFD Rework
Bring back "Ground Reference line" that was missing, Recoloring some elements, and more....
installation
1. navigate to `SimObjects\Airplanes\Aerosoft A330 Professional Base`, you'd see a folder named `Panel_Fallback`, go in it, and you'll see bunch of other folders, look for `displays`
2. replace 2 xml files (`pfd_cpt/fo.xml`) with ones you got from here.

# Potato VC Textures
2k downscaled VC textures for better vram usage/moar fps.
installation
1. Navigate to `SimObjects\Airplanes\Aerosoft A333 RR Professional`, you will see a folder named `texture_FallbackVC`,
2. go in that folder then put these new textures you got from here.

# Fake "Howl/Spool" sound removal
This spool sound reportedly crash some simulators, especially with P3Dv5, disable this would fix the crash.
installation 
1. Navigate to `SimObjects\Airplanes\Aerosoft A333 RR Professional`, you will see a panel folder (named `panel` as you might know), go in it
2. replace `asc.cfg` with the one you gotfrom here

# Reworked Fonts
yes, as it sounds
installation
1. navigate to `C:\Windows\Fonts` then delete these 4 fonts 
	`AirbusDisp Regular`
	`AirbusDisp2 Regular`
	`AirbusPFD Regular`
	`AirbusPFD2 Regular`
2. then put these 4 fonts given from this repo (I know it is replace, but it cannot be done that way, it needs to be deleted first and replace)


# Bug Reports
simply raise an issue like you'd do on normal github opensource repo.



	

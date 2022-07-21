#qb-firegear

A script that makes FiveM peds invulnerable to flames or steam if they are wearing certain clothing items.

You can use this as its own resource or, if using QB-Core, you can drop the file "firegear.lua" into your QB-smallresources/client folder after configuring it.

This script was made for QB-Core using QB-Clothing. If you would like to use it stand-alone or with another framework, change the following lines to suit your needs:

local Torso = GetPedDrawableVariation(ped, 11) --default FiveM native is 3

local Undershirt = GetPedDrawableVariation(ped, 8) --default FiveM native is 8

local Shoes = GetPedDrawableVariation(ped, 6) --default FiveM native is 6

Torso == 315 / Undershirt == 151 / Shoes == 71 // Torso == 325 / Undershirt == 187 // Shoes == 52 --these will definitely change depending on your EUP pack

# Disable Creeper Damage On Explode

Small Minecraft add-on to remove the damage to blocks when a creeper explodes. Damage to a player and other mobs still occurs.

Last tested on Minecraft for Windows 10 version `1.14.60`.

~~~~ powershell
Compress-Archive -Path .\DisableCreeperDamageOnExplodePack\* -DestinationPath .\DisableCreeperExplode.zip
Move-Item -Path .\DisableCreeperDamageOnExplode.zip .\DisableCreeperDamageOnExplode.mcpack
~~~~

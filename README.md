# Half-Life 2: Deathmatch 20th Anniversary update sound fix

## Overview
This fix operates on the server side. For the client to function correctly, it is necessary to enable file downloads from the server with the command: cl_downloadfilter all.

## Description
In the HL2DM update dedicated to the 20th anniversary of Half-Life 2, VALVE dropped support for sound files with a sample rate of 22 kHz. As a result, some sounds, such as charger sounds and health kit pickups, stopped playing in the game. This fix contains original sound files re-sampled to 44.1 kHz, as well as a script file.

## Installation
1. Add the files from the server folder to your game server.
2. Upload the files from the fastdl folder to your web server (FastDL).
3. Add the following files to the download table:
   - sound/itemsfix/ammocrate_close.wav
   - sound/itemsfix/ammocrate_open.wav
   - sound/itemsfix/medcharge4.wav
   - sound/itemsfix/medshot4.wav
   - sound/itemsfix/medshotno1.wav
   - sound/itemsfix/smallmedkit1.wav
   - sound/itemsfix/suitcharge1.wav
   - sound/itemsfix/suitchargeno1.wav
   - sound/itemsfix/suitchargeok1.wav

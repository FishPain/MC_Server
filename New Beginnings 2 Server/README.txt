1. If the start.bat file doesnt work try below methods.  
For Windows -> Add ↓ to a text file and save the text file as start.bat then run file.
java -Xmx4G -Xms4G -jar forge-1.16.4-35.1.32.jar nogui

For Mac -> Add ↓ to a text file and save the text file as start.command then run file.
#!/bin/bash
cd "$(dirname "$0")"
exec java -Xmx4G -Xms4G -jar forge-1.16.4-35.1.32.jar nogui

2. For the first startup, you have to agree to the Mojang EULA. Open eula.txt file, read EULA and change "false" to "true" if you accept it.

3. To enable Biomes O' Plenty in your server, set the level-type setting in server.properties to "biomesoplenty" 

PS: Don't worry about the red cross before you connect to the server.
Always remember to back up your server!
If world doesnt have Biome O' Plenty biomes delete "world" and make sure level-type is "biomesoplenty" in the server.properties, then run server.

If you want to update your server, copy "world" from last version folder and drag it to this version folder.